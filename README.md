**here is the commands to work with go**

- By using first we can go to version
  - my output is  "go version go1.18 windows/AMD "
- Here what we are doing is we are getting apache beam using the second command and we are getting the wordcount by using third commands respectively and by using the fourth command we will generate the output file with word count.

```
1.go version
2.go get -u github.com/apache/beam/sdks/v2/go/pkg/beam
3.go install github.com/apache/beam/sdks/v2/go/examples/wordcount
4.wordcount --input sample.txt --output output
```

After following above command the output file is generated and with word counts 

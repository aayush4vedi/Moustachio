## Moustachio
Hello World program to begin writing Web Apps in Golang.
Source: [Google I/O 2011](https://www.youtube.com/watch?time_continue=8&v=-i0hat7pdpk)
<hr>

### Core Functionality:
* Upload a photo
* Draw moustache on it
* Share it with friends
<hr>

### Demonstration of Go's ability to:
* Serve web pages(using HTML templates)
* Receive uploaded files via HTTP
* Work with file system
* Decode, manipulate, encode images
* Interact with OAuth-authenticated RESTful APIs
<hr>

## APIs

| Client               | API                     | Moustachio |
| :---                 | :--------------:        | ----:      |
|                      | ==GET/==>               | upload     |
|                      | <== <html><form>        | upload     |
| upload.html template |  ==POST/(with image)==> | upload     |
|                      | <==Redirect: /view?id=ID| upload     |
|                      | ==GET/view?id=ID==>     | view       |
| image                |  <== image data==       | view       |

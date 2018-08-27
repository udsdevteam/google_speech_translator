# 셋팅

- gcloud 셋팅

https://cloud.google.com/speech-to-text/docs/reference/libraries

- 소스작성

https://cloud.google.com/speech-to-text/docs/async-recognize

# 자신의 클라우드 버킷 사용

- speech.js에서 아래 내용 수정
> const gcsUri = 'gs://[자신의 버킷 이름]/test.raw';

# input 

- 다음과 같이 file converting이 필요하다

> sudo apt install sox

$ sox hello.wav --channels=1 --rate 16k --bits 16 test.raw

- 구글 클라우드 버킷에 test.raw 를 업로드 한다.

# input file

- test.raw

# output file

- result.txt

# rstp_h264_temporary

#How To Build
1. make clean
2. make
3. ./rtspServer file/path/you/want/to/stream frame

현재 h264 파일 스트림에 올려서 VLC로 테스트 가능하게 임시 완성본 업로드

#TODO
V4L2를 사용해, 파일이 아닌 h264 패킷 자체를 한 번에 넘겨주도록 하는 부분 포팅해야 함.
급하게 올리다보니 rtsp 쪽 class화 작업 대충 해놓아서 리팩토링 한 번 해줘야 함.

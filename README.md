# rstp_h264_temporary

# How To Build

1. make clean
2. make
3. CAM ./rtspServer

1. h264 파일 rtp 스트림에 올려서 VLC 및 ffplay로 테스트 가능
2. rpi camera rev1.3에서 v4l2로 프레임 캡쳐해서 rtp 스트림에 올려 VLC 및 ffplay로 테스트 가능

# How To View In VLC
1. Media -> Open Network Stream
2. rtsp://127.0.0.1:8554
3. 로컬이 아니라면 127.0.0.1을 서버 ip로 대체


# TODO

main.cpp에서 argv로 옵션을 받아 file, camera streaming을 결정하도록 수정해야 한다.
sdp 파싱할 때 중복되는 부분 Utils에 멤버 함수로 등록해야 한다.

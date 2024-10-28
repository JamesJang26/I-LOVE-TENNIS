# I-LOVE-TENNIS

1. docker install
2. clone cvat repository(git clone https://github.com/cvat-ai/cvat.git)
3. export env var(windows: $env:CVAT_HOST="localhost" / linux: export CVAT_HOST=localhost)
4. docker-compose up -d
5. docker ps(status check)
6. http://localhost:8080

다시 켤때는 아래 단계로 진행.

1. Docker Desktop 열고
2. windows: $env:CVAT_HOST="localhost" / linux: export CVAT_HOST=localhost
3. docker-compose up -d
4. http://localhost:8080 접속

openpose로 관절 움직임 추출하고 cvat로 최종 라벨링하여 데이터셋 구축.
해상도, 프레임 통일.
최대한 같은 각도에서 촬영한 영상 사용

해상도 통일하기 위해서 ffmpeg 라이브러리 사용
https://github.com/BtbN/FFmpeg-Builds/releases 여기서 다운받고 환경변수에 추가한 다음, ffmpeg 라이브러리 불러와서 인코딩.




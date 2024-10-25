# I-LOVE-TENNIS

1. docker install
2. clone cvat repository(git clone https://github.com/cvat-ai/cvat.git)
3. export env var(windows: $env:CVAT_HOST="localhost" / linux: export CVAT_HOST=localhost)
4. docker-compose up -d
5. docker ps(status check)
6. http://localhost:8080

openpose로 관절 움직임 추출하고 cvat로 최종 라벨링하여 데이터셋 구축.
해상도, 프레임 통일.
최대한 같은 각도에서 촬영한 영상 사용



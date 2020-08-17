# Convert-audio-type-wav
다른 특정한 음원 파일을 wav 확장자로 변경해주느 툴

## 파라미터 설명 (convert_audio_wav_16k)
- input_dir : 음원파일이 위치하 디렉토리 경로를 작성
- dest_dir : wav 형식으로 변환된 음원 파일을 저장할 디렉토리 경로를 작성
- output_json : 음성인식과 관련된 음원 파일일 시에 스트립트를 정리해주는 기능임 (만약 사용되지 않으면 대충 적고 삭제하면 됨)
- target_sr : 변환할때 수정하 sampling rate 를 지정할 수 있음
- speed : 음원 변환할때 음원의 재새 속도를 변경시킬 수 있음 (None으로 하면 기본으로 됨)
- parallel : 해당 처리를 병렬로 진행할 것인지를 결정하는 부분
- audio_type : 현재 내가 변경할 음원의 original 확장자


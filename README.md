
				로봇의 감정 및 개성을 표현할 수 있는 대화형 음성코퍼스 DB 배포
				===========================================================

목적
====
	본 음성 DB는 산업통상자원부의 산업기술혁신사업으로부터 지원을 받아 한국과학기술원의 주관하에 
	(주)셀바스AI가 구축한 결과물이므로 	연구 목적으로만 활용이 가능하고 상업을 목적으로 활용은 불가함. 
	(No. 10080667, 음원 다양화를 통하여 로봇의 감정 및 개성을 표현할 수 있는 대화음성합성 원천기술 개발)

NOTICE
====
	본 Repository는 아래 기술된 전체 데이터의 5%만 공개된 것이며, 전체 데이터가 활용하고자 하는 기업 또는 
	개인은 아래의 링크된 신청서 작성하여 제출해야함. 
	이후 별도 별도의 심사를 거쳐 자료 제공 여부가 결정되며 미승인시 자료 제공이 거절될 수 있음.
	신청서 : http://naver.me/GaQSRZdm


내용
====
	o 제 작 일 : 2017 ~ 2018년
	o 발성목록 : 낭독체, 대화체
	o DB 구성 및 화자수 
		1) 기본화자 : 여성 1인
		2) 평균음성모델 개발용 : 여성 4인
		3) 화자적응 학습 및 테스트용 : 여성 2인, 남성 2인
		4) 감정 표현 기술 연구를 위한 연구용 DB (일반 대본) : 여성 2인, 남성 3인
			: 일반 대본에 감정을 부여하여 녹음.
			: 일반, 기쁨, 화남, 슬픔		
		5) 감정 표현 기술 연구를 위한 연구용 DB (감정 대본) : 여성 5인, 남성 5인
			: 감정 대본을 사용하여 녹음.
			: 일반, 기쁨, 화남, 슬픔		
	o 음성데이터 파일형식 : PCM WAVE signed 16bits, 22.05kHz, mono
	o 데이터량
		1) 기본화자(여성)
			: 6.500문장(낭독체 1,000문장, 대화체 5,500문장)
			: 음성데이터, 녹음 대본, 대본 철자전사
		2) 평균음성모델 개발용
			: 500문장 x 4명
			: 음성데이터, 녹음 대본, 대본 철자전사
		3) 화자적응 학습 및 테스트용
			: 100문장 x 4명
			: 음성데이터, 녹음 대본, 대본 철자전사
		4) 감정 표현 기술 연구를 위한 연구용 DB (일반 대본)
			: 400문장(감정별 100문장) x 5명
			: 음성데이터, 녹음 대본, 대본 철자전사
		5) 감정 표현 기술 연구를 위한 연구용 DB (감정 대본)
			: 400문장(감정별 100문장) x 10명
			: 음성데이터, 녹음 대본, 대본 철자전사


	o 디렉토리의 내용
		1) Main	- 기본화자(여성), 평균음성모델 개발용, 화자적응 학습 및 테스트용
		2) Emotional - 감정 표현 기술 연구를 위한 연구용 DB
		3) Personality - 개성 표현 음성합성기 개발 고도화를 위한 음성 DB

기타
====
    Contact	 :  서울시 금천구 가산디지털1로 19, 20층
                (주)셀바스에이아이
               	MAIL : TTS_Support@selvas.com


NEWS
====
	New in 2020.08.31
	 - 1st push

1. 프로젝트 개요 / 项目概述
한국어
본 코드는 Flutter 여행 애플리케이션 내 황산시(黄山市) 관광 정보 데이터를 정의한 상수 객체입니다. 자연 명소, 후이저우 고촌, 지역 음식, 3일 여행 코스, 기능 바로가기 및 AI 자동 응답 로직을 통합 구성하며, 앱 내 지역별 여행 페이지에 연동해 사용합니다.
中文
本代码为 Flutter 旅行应用编写的黄山市旅游数据常量对象。整合自然景观、徽派古村落、特色美食、三日游玩路线、功能快捷入口以及智能问答规则，对接应用内对应城市专题页面展示使用。
2. 파일 정보 / 文件说明
한국어
원본 파일 경로: lib/models/city_data.dart
의존 파일: travel_models.dart (전용 데이터 모델 정의)
데이터 객체명: huangshanCity
데이터 타입: CityTravelData
中文
目标文件路径：lib/models/city_data.dart
依赖文件：travel_models.dart（项目自定义数据模型）
数据变量名：huangshanCity
数据类型：CityTravelData
3. 사용 방법 / 使用方式
한국어
위 전체 코드를 lib/models/city_data.dart 파일에 복사하여 추가합니다.
프로젝트 내 전역 cities 도시 목록에 huangshanCity를 등록합니다.
프로젝트를 재실행한 후 황산시 여행 페이지가 정상 로드되는지 확인합니다.
中文
将完整代码复制并添加至 lib/models/city_data.dart 文件中。
在项目的全局 cities 城市列表内注册 huangshanCity 变量。
重启项目，检查黄山专题页面所有内容是否正常加载展示。
4. 데이터 구조 설명 / 数据结构说明
한국어
huangshanCity 객체는 아래 6가지 주요 파트로 구성됩니다.
기본 정보: 도시 ID, 행정 구역, 명칭, 소개 문구, 메인 이미지, 지리/기후/특색 설명
주요 관광지: 황산 풍경구, 훙춘 고촌, 툰시 라오제 (이미지, 소개, 볼거리, 주소, 운영시간 포함)
특색 음식: 취구이위, 마오더우푸, 황산 사오빙 (요리 설명 및 맛 특징)
3일 여행 일정: 시간대별 동선, 소요 시간, 관광 팁이 담긴 완전 추천 코스
퀵 엔트리: 도시소개, 관광지, 음식, AI 문답 4개 메뉴 (아이콘 + 테마 색상 설정)
AI 문답 시스템: 인사말, 키워드 매칭 응답, 기본 답변 규칙
中文
huangshanCity 对象分为六大板块：
基础信息：城市 ID、省市名称、展示文案、轮播图、地理位置、城市简介、气候与特色
热门景点：黄山风景区、宏村古村、屯溪老街，包含配图、简介、游玩亮点、地址及开放说明
特色美食：臭鳜鱼、毛豆腐、黄山烧饼，附带菜品介绍与口味描述
三日行程：分天规划旅行路线，标注时段、停留时长与游玩小贴士
快捷入口：城市介绍、景点、美食、智能问答四大入口，配置图标与主题色
智能问答：欢迎语、关键词匹配回复、默认回复规则
5. 주의사항 / 注意事项
한국어
모든 이미지는 외부 Unsplash 링크이므로 앱 사용 시 네트워크 연결이 필수입니다.
황산 풍경구 운영 시간은 계절·날씨에 따라 조정되므로 방문 전 공식 공지를 확인하세요.
기존 파일에 다른 도시 데이터가 있을 경우 기존 내용을 삭제하지 말고 목록에만 추가하세요.
페이지 아이콘 및 색상은 Flutter 기본 위젯을 사용하며 앱 전체 테마와 연동됩니다.
中文
所有图片均引用 Unsplash 外部链接，运行应用需保证设备联网。
黄山景区营业时间会随季节、天气调整，建议出行前查阅官方通知。
若文件中已存在其他城市数据，请勿删除原有代码，仅在列表中追加本数据即可。
页面图标与配色基于 Flutter 原生组件实现，适配应用整体视觉风格。
6. 운영 환경 / 运行环境
한국어
개발 프레임워크: Flutter
의존 모델: CityTravelData、Attraction、Food 등 travel_models.dart 내 클래스
언어 지원: 한중 양문 동시 표시
中文
开发框架：Flutter
依赖模型：travel_models.dart 中 CityTravelData、Attraction、Food 等实体类
语言适配：支持中韩双语对照展示



<img width="778" height="1304" alt="_cgi-bin_mmwebwx-bin_webwxgetmsgimg__ MsgID=5026266941002012146 skey=@crypt_a3a29693_6c6523b7e086ea4433dac290e43a2aec mmweb_appid=wx_webfilehelper" src="https://github.com/user-attachments/assets/3a08e892-6f78-4aec-a7f1-91742bde8fba" />
<img width="778" height="1304" alt="_cgi-bin_mmwebwx-bin_webwxgetmsgimg__ MsgID=4685176655435745372 skey=@crypt_a3a29693_6c6523b7e086ea4433dac290e43a2aec mmweb_appid=wx_webfilehelper" src="https://github.com/user-attachments/assets/24239f73-0fe7-45e4-8306-8b02a4c1ceb7" />
<img width="778" height="1050" alt="_cgi-bin_mmwebwx-bin_webwxgetmsgimg__ MsgID=4632285938677345055 skey=@crypt_a3a29693_6c6523b7e086ea4433dac290e43a2aec mmweb_appid=wx_webfilehelper" src="https://github.com/user-attachments/assets/ae16dace-7340-4743-8540-c773379be26b" />
<img width="778" height="1391" alt="_cgi-bin_mmwebwx-bin_webwxgetmsgimg__ MsgID=1255571326771664073 skey=@crypt_a3a29693_6c6523b7e086ea4433dac290e43a2aec mmweb_appid=wx_webfilehelper" src="https://github.com/user-attachments/assets/5d14fa60-a8fb-4ffd-8a83-7c93640b9878" />
<img width="778" height="1304" alt="_cgi-bin_mmwebwx-bin_webwxgetmsgimg__ MsgID=9021451747486396128 skey=@crypt_a3a29693_6c6523b7e086ea4433dac290e43a2aec mmweb_appid=wx_webfilehelper" src="https://github.com/user-attachments/assets/3ebf3fcf-adae-4337-82e9-c6cae52f252d" />

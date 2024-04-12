제목: Chat GPT 보고서

조장: 신소재공학부 전자재료공학전공/2023014505/여승은

조원: 신소재공학부 전자재료공학전공/2021113900/최다영
      국악학과 피리전공/2022112217/김하랑
      기계공학부/2019112940/김준엽

1. 개요

![image](https://github.com/victory0300/OSS_13/assets/166486842/08f61ace-ade8-46c1-a06a-dc9b1ce8390c)

챗지피티(ChatGPT)는 Open AI에서 개발한 대화형 인공지능 모델로, 자연어 이해 및 생성 작업을 수행하는 데 사용됩니다. 
이 모델은 GPT(Generative Pre-trained Transformer) 아키텍처를 기반으로 하며, 대규모의 텍스트 데이터로 사전 훈련된 후에 다양한 대화 응용에 활용됩니다.
챗지피티는 텍스트 기반의 질문에 응답하거나 대화를 수행하는 등의 작업에 사용됩니다. 사용자가 제공한 텍스트 입력에 대해 의미를 이해하고 자연스러운 방식으로 
응답을 생성합니다. 이를 통해 챗지피티는 대화형 시스템, 가상 비서, 텍스트 기반의 상담 및 지원 서비스, 이미지 생성 등 다양한 응용 분야에서 활용될 수 있습니다.

2. 라이선스

챗지피티는 Open AI에서 개발되었으며, Open AI는 기술적 발전을 촉진하고 인공지능 기술을 보급하기 위해 투명하고 포괄적인 접근을 취하고 있습니다. 
챗지피티에 대한 라이선스는 Open AI의 사용자 라이선스에 따라 제공되며, 일반적으로 비상업적 용도 및 연구 목적으로 무료로 사용할 수 있습니다. 
하지만, GPT 3.5모델에서 GPT4모델을 사용하기 위해선 매달 20달러를 추가로 지불해야 합니다. 또한, 기업이 제품 및 서비스를 Chat GPT를 활용해 개발하고자 하는 경우, 
계약을 하여 상업적 라이선스를 확보할 수 있습니다. 사용자는 Open AI의 라이선스 및 이용 약관을 확인하고 적절한 라이선스를 취득해야 합니다.

3. 주요기능

저희는 Chat GPT의 기능의 성격에 따라 정보 전달 기능, 창의적인 기능, 정보 분석 기능, 기타 기능 총 네가지로 분류했습니다. 


3-1. 정보 전달 기능

Chat GPT는 Transformer 아키텍처를 기반으로 합니다. Transformer 아키텍처는 딥러닝 아키텍쳐 중의 하나입니다. 
이는 입력된 모든 단어를 병렬로 동시에 처리하여 보다 빠른 응답을 사용자에게 제공하는 것이 특징입니다. 이것은 Attention 메커니즘을 통해 구현할 수 있습니다. 

① Attention 메커니즘 작동 방식

Attention 메커니즘은 주로 쿼리, 키, 값 세가지 주요한 요소를 사용합니다. 
쿼리는 어텐션을 계산하기 위한 대상을 의미합니다. 보통 현재 처리 중인 단어나 문장의 표현을 쿼리라고 할 수 있습니다. 
키는 입력 시퀀스의 각 요소에 대한 정보입니다. 
이 정보는 인코더의 출력이며, 쿼리와의 유사도를 측정하는 데 사용됩니다. 값은 각 키에 해당하는 값으로, 보통 디코더에서 출력할 정보입니다. 
이러한 세가지 요소를 바탕으로 Attention메커니즘이 수행됩니다. 
주어진 쿼리에 대해 입력 시퀀스의 각 키와의 유사도를 계산하고, 이 유사도에 따라 각 값의 가중합을 계산하여 출력을 생성합니다. 이 과정을 통해 모델은 입력 시퀀스의 특정 부분에 주의를 기울일 수 있어 문장을 빨리 이해하고 다음 대화를 예측할 수 있습니다. 

② Attention 메커니즘 활용 방식

Chat GPT는 이러한 Attention을 여러 개로 분할하여 동시에 처리하는 Multi-Head attention 기능을 사용합니다. 
이를 통해, 여러 관점에서 문맥을 파악하고 이해하며 보다 빠르게 이해하는데 도움을 주어 사용자에게 빠른 응답을 제공할 수 있는 것입니다. 
또한, Chat GPT는 대규모의 데이터로 사전학습이 되어 있는 상태로, 일반적인 언어 패턴이나 문맥을 이해하는 것을 수월히 할 수 있습니다. 
이러한 기능은 추가적인 학습을 하는데 소요되는 시간을 줄일 수 있습니다. 
그리고, Transformer 아키텍쳐는 포지션 인코딩을 통해 입력순서를 이해하도록 합니다. 
이는 각 입력 단어의 위치 정보를 임베딩에 추가하여 모델이 단어의 순서를 이해할 수 있게 돕는 것입니다. 
이렇게 임베딩된 정보를 Transformer는 인코더-디코더 아키텍처를 사용하여 번역 및 기타 시퀀스 변환 작업을 수행합니다. 
인코더에서 임베딩된 최종 정보를 출력하면 디코더는 이 중간 표현을 기반으로 출력 시퀀스를 생성합니다. 

③ 활용방안

이를 통해, 사용자는 원하는 정보와 그에 맞는 대답을 사용자의 언어로 보거나 들을 수 있습니다.
Chat GPT는 이와 같은 기능들을 활용하여 사용자에게 빠른 응답을 제공하고 광범위한 분야의 정보를 제시할 수 있습니다. 
이러한 장점들로 최근 많은 인공지능에 Chat GPT를 기반으로 하여 출시되고 있습니다. 
하지만, 아직까지 2022년 9월까지의 데이터를 기반으로 하고 있기 때문에 최신 정보를 받기 힘들다는 점과, 전문적인 분야에 관련하여 정확한 정보를 항상 제공하지 못한다는 한계가 있습니다. 


3-2. 창의적인 기능 - 이미지 생성 기능(DALL·E)

DALL·E는 Open AI가 개발한 창의적인 이미지 생성 기술로, GPT-3와 같은 딥러닝 모델을 활용하여 사용자가 제시한 텍스트 설명에 맞는 이미지를 생성할 수 있습니다.
이러한 기술은 이미지 생성 분야에서 기존의 데이터셋에 의존하지 않고 창의적이고 독특한 이미지를 생성할 수 있다는 점에서 대단한 기술적 성과라고 할 수 있습니다.
최근 CHAT GPT에 DALL·E3가 내장되면서 사용자는 CHAT GPT 대화창 안에서 간단한 문장을 설명함으로써 이미지를 생성 할 수 있게 되었습니다.

① DALL·E의 작동 방식

 DALL·E의 작동 방식은 크게 두 가지 요소로 설명할 수 있습니다. 첫 번째는 GPT입니다. DALL·E는 GPT 아키텍처의 변형을 기반으로 합니다. 
GPT는 텍스트를 생성하고 이해하는 데 사용되는 인공지능 모델로, 텍스트 시퀀스를 학습하고 그 다음에 올 수 있는 가장 적절한 단어 또는 문장을 예측합니다. 
DALL·E에서 GPT는 텍스트 설명을 이해하고 해당 설명을 기반으로 이미지를 생성하는 데 사용됩니다.
 DALL·E의 또 다른 중요한 구성 요소는 생성적 적대 신경망 (GAN)입니다. GAN은 실제같은 이미지를 생성하기 위해 경쟁하는 두 개의 신경망, 생성자와 판별자로 구성됩니다. 
생성자는 텍스트 설명에 부합하는 이미지를 생성하고, 판별자는 실제 이미지와 생성된 이미지를 구별합니다. 이 과정을 통해 생성자는 점차 실제와 더 비슷한 이미지를 생성할 수 있게 됩니다.
 DALL·E는 GPT와 GAN을 결합하여 텍스트 설명을 이미지로 변환합니다. 사용자가 제공한 텍스트 설명을 이해하고, 이를 기반으로 이미지를 생성하기 위해 
GPT를 사용하고, 생성된 이미지의 품질을 향상시키기 위해 GAN을 활용합니다. 이러한 과정을 통해 DALL·E는 매우 다양한 텍스트 설명에 따라 
다양한 스타일의 이미지를 생성할 수 있습니다.

② DALL·E의 장점

텍스트 기반 이미지 생성: DALL·E는 텍스트 설명을 입력으로 받아 해당하는 이미지를 생성합니다. 이는 기존의 이미지 생성 모델들과는 다른 방식으로 작동하는데, 
사용자가 텍스트로 이미지를 설명하면 DALL·E는 이를 이해하고 해당하는 이미지를 생성합니다. 또, 명령어에 대한 높은 이해도가 특징인데, DALL·E3은 이전 모델보다
훨씬 많은 뉘앙스와 디테일을 이해하여 명령어에 부합하는 매우 정확한 이미지를 만들 수 있다는 장점이 있습니다.

창의적 이미지 생성: DALL·E는 사용자가 입력한 텍스트에 따라 창의적이고 독특한 이미지를 생성합니다. 이는 이전의 데이터셋에 의존하지 않고도 
새로운 이미지를 만들어낼 수 있는 능력을 갖추고 있습니다.

대규모 텍스트-이미지 모델 훈련: DALL·E는 대규모 데이터셋을 활용하여 훈련되었습니다. 이를 통해 다양한 텍스트-이미지 관계를 학습하고 
이를 바탕으로 이미지를 생성하는데 더욱 정교한 방식을 사용할 수 있게 되었습니다.

사용자 정의 이미지 생성:DALL·E는 특정한 이미지를 생성하는 대신, 사용자가 원하는 특정한 스타일이나 속성을 갖춘 이미지를 생성할 수 있습니다. 
예를 들어, "파란색 삼각형이 위에 놓인 빨간색 집"과 같은 텍스트 입력에 대한 이미지를 생성할 수 있습니다. 다른 이미지 생성 모델들에 비해 사용자의
모든 요청사항을 잘 반영한다는 장점이 있습니다.

다양한 응용 분야: DALL·E는 디자인, 광고, 문서 작성 등 다양한 분야에서 활용될 수 있습니다. 이를 통해 창의적이고 독특한 이미지를 필요로 하는 
다양한 응용 프로그램에서 사용될 수 있습니다.

챗GPT와의 통합: DALL·E는 챗GPT 대화창에서 이미지생성, 편집, 업스케일까지 모든 작업이 가능합니다. 챗GPT에 아이디어를 제공하면 
챗GPT는 아이디어를 실현할 수 있는 맞춤형 프롬프트를 자동으로 생성하고 이미지를 생성합니다.

정확한 텍스트 구현: 미드저니, 스테이블 디퓨전과 같은 다른 이미지 생성모델들도 아직까지 텍스트를 정확히 구현하지는 못합니다. 하지만
DALL·E3는 텍스트도 정확히 구현 할 수 있어 실질적인 활용도가 높습니다.

③ DALL·E 유의점

CHAT GPT의 DALL·E 기반 이미지 생성 기능은 혁신적인 기술로 평가되며, 사용자에게 새로운 경험과 편의성을 제공합니다. 
그러나 DALL-E가 이미지를 생성할 때 사용하는 데이터셋과 알고리즘에 따라, 이 기술이 만들어내는 이미지가 성적, 인종, 성별 등과 같은 특정 집단을 차별하거나
모욕적인 이미지를 생성할 수도 있습니다. 또한, 생성된 이미지가 실제로 존재하는 사물과 거의 비슷하다면, 이러한 이미지를 잘못 사용하거나 남용할 가능성이 있습니다. 
이러한 문제를 해결하기 위해서는 이러한 기술을 사용하는 사람들의 책임적인 사용이 필요하며, 이러한 기술의 발전이 일어날 때마다 적극적인 대응이 필요합니다.
이에 Open AI는 유해세대 예방을 위해 공인의 이름을 묻는 요청 거부 완화 기능을 탑재하고, 공개 인물 생성 및 시각적 과잉/과소 표현과 관련된 유해편견과 같은 
위험 영역 평가를 진행하여 이러한 문제를 완화하기 위해 노력하고 있습니다.


3-3. 정보 분석 기능 - 고급 데이터 분석(Advanced Data Analysis)

① 소개

Advanced Data Analysis는 Chat GPT가 Python 코드를 직접 실행하여 결괏값을 산출하는 기능입니다.
기존에는 Code Interpreter라고 불렸는데, 이 명칭만 봤을 때 프로그래밍을 하는 사람들에게 유용한 것으로 보이지만 실제로는 데이터 분석에 더 적합하여 주 사용 용도를 확실하게 드러내기 위해 이름을 바꾼 것으로 추정됩니다.
Advanced Data Analysis는 텍스트 및 이미지 파일, PDF, 코드 또는 기타 데이터 파일과 같은 전체 문서, 오디오 및 비디오를 포함한 다양한 파일 형식을 지원합니다.
성능은 파일 유형에 따라 다르지만 특히 .csv 및 .txt와 같은 데이터 파일용으로 설계되었습니다.
현재 Advanced Data Analysis는 Python을 사용하여 작업을 수행하지만 여전히 다른 프로그래밍 언어를 이해하고 해독할 수 있는 기본 ChatGPT 모델을 사용합니다.
이로 인해 프로그래밍 언어 간에 코드를 효과적으로 변환하거나 Python 이외의 언어로 된 파일을 이해할 수 있습니다.

② 기능

(1) 데이터 시각화: 데이터를 그래프나 차트 등 시각적으로 표현하여 패턴이나 추세를 파악할 수 있습니다.

![image](https://github.com/victory0300/OSS_13/assets/166524922/58f12466-c198-4eb8-8905-9044f9c652a2)


(2) 머신 러닝: 데이터를 기반으로 모델을 학습시키고 미래의 행동을 예측할 수 있습니다.
예를 들어 선형 회귀, 의사 결정 나무, K-평균 클러스터링 등의 알고리즘을 사용하여 이루어집니다.

(3) 시계열 분석: 시간에 따라 변하는 데이터를 분석하고 예측하는 것입니다. 주식 시장 예측, 날씨 예보, 경제 지표 분석 등에 활용됩니다.

(4) 자연어 처리(NLP): 텍스트 데이터를 분석하고 이해하는 것입니다. 감정 분석, 텍스트 분류 등을 수행할 수 있습니다.

(5) 멀티미디어 생성 및 편집: GIF 애니메이션 생성, 이미지 편집 및 변환 등의 작업을 간편하게 수행할 수 있습니다.

③ 활용

(1) 기업

데이터 분석, 시각화, 파일 변환 등 복잡한 작업을 간단하게 수행할 수 있어 기업의 업무 효율성을 증대시킬 수 있습니다.
특히 주식 데이터 분석이나 설문조사 결과 분석 등의 작업을 쉽게 처리할 수 있어, 기업의 의사결정 과정에 큰 도움을 줄 수 있습니다.
게다가 기업은 데이터 분석에 소요되는 시간을 줄일 수 있어 비용 절감과 함께 빠른 의사 결정이 가능합니다.

(2) 일반 사용자

복잡한 코드 작성 없이도 데이터 시각화, 이미지 편집, GIF 생성 등의 작업을 수행할 수 있기 때문에, 코드가 익숙하지 않더라도 다양한 작업을 수행할 수 있습니다.
복잡한 데이터 분석 작업도 클릭 몇 번으로 완료할 수 있습니다.


3-4. 기타 기능

Chat GPT는 자연어를 이해하고 사용자의 질문이나 요청을 처리할 수 있어 문장을 이해하고 적절한 답변을 생성합니다.
사용자의 질문이나 주제에 대해 응답을 생성할 수 있습니다. 문장을 자연스럽게 생성하여 다양한 주제에 대한 대화를 이끌어냅니다.
온라인에서 다양한 주제에 관한 정보를 검색하고 해당 정보를 사용자에게 제공할 수 있습니다.

텍스트 생성 및 편집에 활용될 수 있습니다. 예를 들어, 자기소개서 수정 및 첨삭 같이 글쓰기 도우미로 활용할 수 있습니다.
다양한 종류의 문서를 생성할 수 있습니다. 보고서, 이메일, 기사, 소설 등을 작성 하는데 활용될 수 있습니다.
이전 대화 기록을 기억하고 해당 정보를 활용하여 일관된 대화를 유지할 수 있습니다. 따라서 사용자의 이전 대화 내용이나 설정을 기반으로 개인화된 서비스를 
제공할 수 있습니다. 또, 사용자의 감정을 인식하고 적절한 대응을 할 수 있습니다. 이를 통해 더 나은 상호작용이 가능합니다.
따라서 사용자가 혼자 있을 때 동반자 역할을 할 수 있습니다.사용자와의 대화를 통해 게임을 진행하거나 재미있는 상호 작용을 제공할 수 있습니다. 
예를 들어, 퀴즈, 이야기 만들기, 재미있는 질문에 대한 대답 등이 가능합니다.

Chat GPT는 사용자가 문제를 해결하거나 질문에 답변하는데 도움을 줄 수 있습니다. 상담 및 지원 서비스에 적용될 수 있습니다.
학습자들에게 도움을 줄 수 있습니다. 수학 문제 풀이, 언어 공부, 과학 개념 이해 등 다양한 학습 분야에서 도움을 줄 수 있습니다.
사용자가 사실 확인이 필요한 정보를 요청할 때 신뢰할 수 있는 소스를 기반으로 정보를 제공할 수 있습니다.

개발자들이 자연어 처리나 대화형 시스템을 구축할 때 사용될 수 있는 도구로 활용될 수 있습니다. API를 통해 다양한 플랫폼에 적용될 수 있습니다.

Chat GPT는 사용자의 취향과 관심사를 기반으로 제품이나 서비스를 추천할 수 있습니다. 예를 들어, 영화나 음악 추천, 쇼핑 도우미 등이 있습니다.

4 결론

저희는 Chat GPT의 정보 전달 기능, 창의적 기능, 정보 분석 기능, 그 외 기타 여러기능까지 분석해 보았습니다. Chat GPT는 사용자의 요구에 맞는 결과물을 제시하기 위해
다양한 기능적 특성을 포함하고 있었습니다. 이러한 특징 때문에 현재 많은 기업들에서 Chat GPT를 기반으로 한 소프트웨어나 제품들을 출시하고 있습니다.
이러한 인공지능의 발전은 저희의 삶에 큰 변화를 가져다 줄 것이며 앞으로 인간 사회의 발전에 많은 기여를 할 것입니다.

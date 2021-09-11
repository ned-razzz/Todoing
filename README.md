# Todoing

개인적으로 사용하기 위한 웹 스케줄러 프로젝트입니다.



## 주요 기능

### 스케줄러 (Scheduler)

**Overview (전체적으로)**
이미 시중에 존재하는 Calendar의 기능을 말합니다.
<u>일정의 저장/관리 기능</u>과 <u>알림 기능</u>이 포함되어 있습니다.

**Daily Scheduler (일별 스케줄러)**
**Daily Scheduler**는 <u>오늘 해야 하는 일</u>을 보여주는 일종의 표시 기능을 말합니다.
<u>오늘 할 일을 저장하는 과정</u>과 <u>오늘 해야 하는 일을 보여주는 장치</u> 모두를 의미합니다.

**Weekly Scheduler (주별 스케줄러)**
**Weekly Scheduler**는 [에브리타임 서비스](https://everytime.kr/)와 같이 스케줄을 미리 저장하고 <u>일주일 단위의 스케줄을 보여주는</u> 기능을 말합니다.
**Weekly Scheduler**에서 보여주는 일주일간 스케줄은 앱 상에서의 위젯을 통해 보여지게 됩니다. (시각적으로)

**Monthly Scheduler (월간 스케줄러)**
일반적인 *Calendar*가 가지고 있는 <u>스케줄을 저장하고 알림을 통해 알려주는</u> 기능을 말합니다.
**Monthly Scheduler/Calendar**는 앱 내부의 **일정/캘린터** 매뉴에서 보여지게 됩니다.



### Daily Report

사용자로부터 **Daily Scheduler**에 따라 <u>하루의 마지막</u>에 <u>그 날의 **Daily  Scheduler**</u>에 대한 달성률을 확인합니다.
확인된 *Achievement rate*는 **Weekly Scheduler** 또는 **Monthly Scheduler**를 통해 보여집니다.



### 우선순위 Indicator

**우선순위 Indicator**를 통해 <u>기간이 정해지지 않은 일정</u>에 대해 우선순위 순서대로 볼 수 있는 화면을 제공합니다.



### Temporary Note

**Scheduler**와 **메인 화면** 등 필요한 곳에 필요할 때 사용할 수 있도록 **Temporary Note**를 배치합니다.



## Main Function

### Scheduler

* Weekly Scheduler

* Daily Scheduler

  > **Temporary Note** function
  >
  > On the **Daily Scheduler** page, can write temporary memo to memorize something they need.

* Calendar (w. Achievement rate indicator)

> Every **Scheduler** function has **delay** function.
> It can delay today's schedule for another day.



### Daily Report

* Achievement Checker
* Simple note for daily journey.



## Specification

### Front-end

* HTML
* CSS3
* Javascript

### Back-end

* express.js

* Echo

  > To be determine.


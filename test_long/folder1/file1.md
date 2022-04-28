# SIEM

![image](/assets/images/blog_LogC.png)



<details>
<summary>Log Collector > Custom Application</summary>
<div markdown="1">
<!-- ![image](/assets/images/blog_LogC.png) -->


## Log Collector > Custom Application
# 응용프로그램 로그 분석 - Postfix

[![you01](/assets/images/you01.png)](https://youtu.be/YmWLsadlIdM)
<!-- {%include video.html id="9YtI-plPXm8"%} -->

PLURA V5는 응용프로그램에 대한 로그를 업로드 설정을 이용하여 수집할 수 있습니다.

> 1. 응용프로그램 원본 로그 업로드를 위해서는 관리>목록>응용프로그램 태그를 등록해주어야 합니다.
>
> 2. 수집할 경로를 파악하고 있어야 합니다.

응용프로그램 로그 업로드 설정하기[1] : <http://blog.plura.io/?p=17653>

**응용프로그램 로그는 "LogStash"를 이용하여 컬럼을 분리할 수 있습니다.**

Logstash는 다양한 소스로부터 데이터를 수집하고 곧바로 전환하여 원하는 대상에 전송할 수 있도록 하는 경량의 오픈 소스 서버츨 데이터 처리 파이프라인입니다.

Logstash를 사용하면 시스템 로그, 웹 사이트 로그, 애플리케이션 서버 로그 등 다양한 데이터를 원본에서 비정형 데이터를 쉽게 수집할 수 있습니다.[2]

</div>
</details>
source: `{{ page.path }}`

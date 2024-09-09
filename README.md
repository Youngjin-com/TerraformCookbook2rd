# 테라폼 쿡북

<img src="https://www.youngjin.com/images/book_cover/9788931475876.jpg" height="350px" style="border: 2px solid grey;">

[테라폼 쿡북(영진닷컴)](https://blog.naver.com/ydot/223490653405)

『테라폼 쿡북』는 테라폼을 이용해서 코드형 인프라를 구축하는 방법을 자세히 다룬다. 테라폼의 설치부터 시작해서 구축하고, CLI를 사용하여 워크플로우를 수행하며, 모듈을 사용하는 방법을 설명한다. 주요 클라우드 프로바이더인 애저, AWS, GCP에서 인프라를 구축하는 실질적인 방법을 포함하여, 쿠버네티스와의 통합도 다룹니다. 또한, 테라폼의 고급 기술이라고 할 수 있는 테스트, CI/CD 파이프라인 통합, 협업 플랫폼인 테라폼 클라우드 사용법도 설명한다. 다양한 예제를 통해 테라폼 구성을 작성하고, 다른 도구와의 통합 사례도 제시한다..

**저자** 미카엘 크리프  
**역자** 강진우  
**발행일** 2024년 07월 29일  
**크기** 188*257mm   
**쪽수** 744쪽  
**가격** 44,000원  
**ISBN** 9788931475876  

<br>

## 새로운 판과 이전 판 비교:  
-	Azure, AWS, GCP 인프라를 Terraform으로 프로비저닝하는 실제 사례.
-	Terraform을 Docker와 Kubernetes에 사용하는 방법, 고급 GitOps 실습, 코드 및 보안 준수를 확인하기 위한 다양한 도구로 Terraform 구성을 테스트하는 새로운 챕터.
-	Terraform Cloud를 마스터하기 위한 전용 챕터.
-	자주 발생하는 Terraform 문제 및 해결책에 대한 트러블슈팅.
  
<br>

## 💡소프트웨어 및 하드웨어 목록

| 필요한 소프트웨어    | 소프트웨어 링크    | 하드웨어 사양    | 요구되는 OS    |
|:---:  |:---:  |:---:  |:---:  |
| Terraform Cli, 버전 ≥1.5  | [https://developer.hashicorp.com/terraform/downloads](https://developer.hashicorp.com/terraform/downloads) | 최신 컴퓨터에서 작동 | Windows, MacOS, Linux  |
| Terraform Cloud  | [https://app.terraform.io/app/](https://app.terraform.io/app/) | 최신 컴퓨터에서 작동 | 해당 없음 (모든 브라우저)  |
| Azure  | [https://azure.microsoft.com/en-in](https://azure.microsoft.com/en-in) | 최신 컴퓨터에서 작동  | 해당 없음 (모든 브라우저) |
| Python 버전 ≥ 3.11  | [https://www.python.org/downloads/](https://www.python.org/downloads/) | 최신 컴퓨터에서 작동  | Windows, MacOS, Linux |
| PowerShell 스크립팅  | [https://learn.microsoft.com/en-us/powershell/scripting/install/installing-powershell-on-windows?view=powershell-7.3](https://learn.microsoft.com/en-us/powershell/scripting/install/installing-powershell-on-windows?view=powershell-7.3) | 최신 컴퓨터에서 작동 | Windows, MacOS, Linux  |
| Shell 스크립팅  | - | 최신 컴퓨터에서 작동 | Linux / WSL / MacOS  |
| Golang 버전 ≥1.20  | [https://go.dev/doc/install](https://go.dev/doc/install) | 최신 컴퓨터에서 작동  | Windows, MacOS, Linux |
| Azure CLI  | [https://learn.microsoft.com/en-us/cli/azure/install-azure-cli](https://learn.microsoft.com/en-us/cli/azure/install-azure-cli) | 최신 컴퓨터에서 작동  | Windows, MacOS, Linux |
| Azure DevOps  | [https://azure.microsoft.com/en-in/products/devops](https://azure.microsoft.com/en-in/products/devops) | 최신 컴퓨터에서 작동 | 해당 없음 (모든 브라우저)  |
| GitHub  | [https://desktop.github.com/](https://desktop.github.com/) | 최신 컴퓨터에서 작동 | 해당 없음 (모든 브라우저)  |
| Git  | [https://git-scm.com/downloads](https://git-scm.com/downloads) | 최신 컴퓨터에서 작동  | Windows, MacOS, Linux |
| Ruby 버전 ≥ 3.0.0  | [https://www.ruby-lang.org/en/downloads/](https://www.ruby-lang.org/en/downloads/) | 최신 컴퓨터에서 작동  | Windows, MacOS, Linux |
| Docker  | [https://www.docker.com/](https://www.docker.com/) | 최신 컴퓨터에서 작동 | Windows, MacOS, Linux  |
| Terragrunt  | [https://terragrunt.gruntwork.io/docs/getting-started/install/](https://terragrunt.gruntwork.io/docs/getting-started/install/) | 최신 컴퓨터에서 작동 | Windows, MacOS, Linux  |
| Jq  | [https://jqlang.github.io/jq/download/](https://jqlang.github.io/jq/download/) | 최신 컴퓨터에서 작동  | Windows, MacOS, Linux |
| Infracost  | [https://www.infracost.io/](https://www.infracost.io/) | 최신 컴퓨터에서 작동  | Windows, MacOS, Linux |
| kubectl / Helm  | [https://kubernetes.io/docs/tasks/tools/](https://kubernetes.io/docs/tasks/tools/) | 최신 컴퓨터에서 작동 | Windows, MacOS, Linux  |
| Node.js  | [https://nodejs.org/en/download](https://nodejs.org/en/download) | 최신 컴퓨터에서 작동 | Windows, MacOS, Linux  |"
 
<br>

## 💡실습용 예제 파일 & 소스 코드
도서 실습에 필요한 예제 파일과 소스 코드는 챕터별로 구성하였으며, 깃허브 저장소뿐만 아니라 [영진닷컴 홈페이지](https://www.youngjin.com/reader/pds/pds.asp)에서도 다운로드받을 수 있습니다.  
코드 작성 시에는 코드를 직접 입력하거나, 책에서 제공하는 소스 코드 파일을 사용하세요.

<br>

## 💡문의 및 정오표
- [문의](mailto:Support@youngjin.com)
- [정오표](https://www.youngjin.com/Artyboard/mboard.asp?strBoardID=errata)




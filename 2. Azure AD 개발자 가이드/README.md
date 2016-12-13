Azure AD에 대한 전반적인 내용을 소개드렸으니 이제 본격적으로 Azure AD를 사용하는 방법에 대해 알아볼까 합니다. 
소개드릴 문서는 ['Azure Active Directory 개발자 가이드'](https://docs.microsoft.com/ko-kr/azure/active-directory/active-directory-developers-guide) 입니다. 주요 기능에 대한 설명과, 지원 플랫폼별로 가이드 문서가 잘 정리되어 있어 천천히 읽어보실만 합니다.
![Supported Platform](AzureAD/2. Azure AD 개발자 가이드/AzureAD-Platforms.PNG ) 

위 문서를 요약하자면 우선 개요로 총 다섯가지의 문서를 안내합니다. 각각의 내용은 아래와 같습니다. 

1. Azure AD 통합의 장점 
* 응용프로그램과 Azure AD의 통합이 가져올 장점에 대한 설명입니다.
2. Azure AD 인증 시나리오
* Azure AD는 다양한 종류의 응용프로그램(e.g. 웹 브라우저, SPA, Native 응용프로그램 등)에 인증 및 권한부여를 할 수 있습니다. 각 시나리오 별 인증 과정에 대한 상세한 내용을 담고 있습니다.   
3. Azure AD와 응용 프로그램 통합
* Azure AD를 사용하는 경우 조직에서 사용할 외부 응용프로그램을 추가하고 관리하는 방법에 대한 설명입니다. 
4. Azure AD Graph API
* 위 3번의 대표적인 시나리오가 Microsoft의 Office 365와 통합하는 시나리오입니다. Office 365와 통합하게 되면, Graph API(REST API)를 통해 메일이나 일정등의 정보를 응용프로그램에서 호출할 수 있습니다. 
5. Azure AD 인증 라이브러리
* Azure AD 인증 추가 /통합 / Graph API 사용을 손쉽게 구현하기 위해서, Microsoft는 여러 라이브러리를 제공하고 있습니다. .NET Framework 뿐만아니라, JavaScript, Objective-C, Android 등에 대한 인증 라이브러리를 지원하고 있어 링크와 관련내용들을 상세히 담고 있습니다.

그 밖에도 여러 참고 자료와 샘플코드, 영상, 블로그 자료까지 모두 담고 있어 Azure AD에 관심이 있는 개발자라면 꼭 한번 참고해 보실만 합니다.

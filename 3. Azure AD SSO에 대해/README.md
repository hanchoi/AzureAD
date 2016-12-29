AAD(Azure AD)를 사용하여 SSO(Single Sign-On)을 구현하고자 하신다면 다음 링크의 문서를 읽어보실만 합니다. 
[Azure Active Directory의 응용 프로그램 액세스 및 Single Sign-On이란 무엇입니까?](https://docs.microsoft.com/ko-kr/azure/active-directory/active-directory-appssoaccess-whatis)

요약하자면 AAD는 응용 프로그램에 로그인 하는데 있어, 총 세가지 방식의 SSO를 지원합니다. 

1. 페더레이션된 SSO 
* SAML 2.0, WS-Federation, OpenID Connect와 같은 프로토콜을 사용하여, 개발한 응용프로그램에 AAD 인증을 추가한 경우입니다. 
2. 암호 기반 SSO
* 관리자가 3rd Party SaaS 응용프로그램의 계정과 AAD 계정을 연동하는 경우입니다. 예를 들어 조직에서 공용으로 사용하는 트위터 계정이 있는경우, 이 계정과 암호를 사용자의 AAD 계정에 연동시킬 수 있습니다. 이 때 사용자는 브라우저 확장이나 모바일 앱을 통해, AAD 계정을 사용하여 트위터 계정에 로그인을 할 수 있습니다. 이 때 관리자가 설정한 트위터 계정과 암호는 안전한 암호 저장소에 저장됩니다.  
3. 기존에 구현된 SSO를 이용
* 기존에 구현된 SSO가 있는 조직이라면 이를 AAD에서 계속 활용할 수 있습니다. SSO에 대한 링크를 Azure AD의 액세스 패널에 배치할 수 있습니다. 

IT 관리자 분들은 2번과 3번에 대해 관심이 있으실 것 같습니다. 위에서 소개 드린 링크의 문서 혹은 번역이 수정된 본 리포지토리의 [문서](\active-directory-appssoaccess-whatis.md)를 참조하시면 상세한 내용을 살펴 보실 수 있습니다.

개발자 분들은 1번의 페더레이션된 SSO를 구현하는데 관심이 있으실 것 같습니다. 페더레이션된 SSO를 구현하시면 마이크로소프트가 운영하는 [Azure Appsource](https://appsource.microsoft.com/ko-kr/)에 응용프로그램을 등록하실 수도 있습니다. 
페더레이션된 SSO를 구현하는 방법은 시나리오별로 아래 샘플들을 참고하시면 좋을 것 같습니다. (시간이 허락한다면 일부 번역하여 본 리포지토리에 올리겠습니다.)

[WebApp-MultiTenant-OpenIdConnect-DotNet](https://github.com/AzureADSamples/WebApp-MultiTenant-OpenIdConnect-DotNet)

[WebApp-WebAPI-MultiTenant-OpenIdConnect-DotNet](https://github.com/AzureADSamples/WebApp-WebAPI-MultiTenant-OpenIdConnect-DotNet)

[NativeClient-WebAPI-MultiTenant-WindowsStore](https://github.com/AzureADSamples/NativeClient-WebAPI-MultiTenant-WindowsStore)

위 샘플들은 Azure AD의 인증 시나리오에 대한 기본적인 이해를 필요로 합니다. 아래 링크를 참고하시면 좋을 것 같습니다. 

[Azure AD의 인증 시나리오](https://docs.microsoft.com/ko-kr/azure/active-directory/active-directory-authentication-scenarios)


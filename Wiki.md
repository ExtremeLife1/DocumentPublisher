



### Microsoft.WindowsAPICodePack.Shell

폴더 찾기 다이얼로그(CommonOpenFolderDialog)를 사용하기 위해서 nuget을 통해 추가해야 됨



축자 문자열(Verbatim String)에서는 이스케이프 문이 존재하지 않는다. 큰따옴표는 예외인데, 큰따옴표(")를 하나 붙이기 위해서 축자문자열에 큰따옴표 두개("")를 입력해야 한다.

 축자 문자열 사용을 위해서는 문자열 시작 따옴표 앞에 @를 붙이면 된다.

주로 파일 경로를 포함한 문자열 텍스트를 나타낼 때 가독성을 높이기 위해서 축자 문자열을 사용한다.

주의할 점은, 컴파일 시 축자 문자열은 모두 동일한 이스케이프 시퀀스가 포함된 일반 문자열로 변환된다. 따라서 디버거 조사식 창에서는 축자 문자열을 확인할 경우 소스 코드의 축자 버전이 아닌 컴파일러에 의해 추가된 이스케이프 문자가 포함되어 나타난다.


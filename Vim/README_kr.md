# Vim은 무엇인가?
Vim은 오래됐지만 좋은 UNIX 편집기 Vi의 개선된 버전입니다. 다중 레벨 실행 취소, 구문 강조, 명령 행 히스토리, 온라인 도움말, 맞춤법 검사, 파일 이름 완성, 블록 조작, 스크립트 언어 등 많은 새로운 기능이 추가되었습니다. GUI (Graphical User Interface)도 있습니다. 여전히 Vi 호환성이 유지되고 Vi를 사용하고 있는 사람들은 집에서 느낄 것입니다. runtime/doc/vi_diff.txtVi와의 차이점을 참조하십시오.
이 편집기는 프로그램 및 기타 일반 텍스트 파일을 편집할 때 매우 유용합니다. 모든 명령은 일반 키보드 문자로 제공되므로 열 손가락으로 입력할 수 있는 사용자는 매우 빠르게 작업할 수 있습니다. 또한 기능 키는 사용자가 명령에 매핑(mapping이란 하나의 값을 다른 값으로 대응시키는 것) 할 수 있으며 마우스를 사용할 수 있습니다.
Vim은 MS-Windows (NT, 2000, XP, Vista, 7, 8, 10), Macintosh, VMS 및 거의 모든 종류의 UNIX에서 실행됩니다. 다른 시스템으로 포팅(porting은 컴퓨터 과학에서 실행 가능한 프로그램이 원래 설계된 바와 다른 컴퓨팅 환경에서 동작할 수 있도록 하는 과정)하는 것은 그리 어렵지 않아야 합니다. 이전 버전의 Vim은 MS-DOS, MS-Windows 95 / 98 / Me, Amiga DOS, Atari MiNT, BeOS, RISC OS 및 OS / 2에서 실행됩니다. 이들은 더 이상 유지되지 않습니다.

# 배포
자주 사용하는 패키지 관리자를 사용하여 Vim을 설치할 수 있습니다. Mac 및 Linux에는 Light한 버전의 Vim이 이미 설치되어 있으므로 더 많은 기능을 원하면 Vim을 설치해야 합니다.

Unix, PC, Amiga 및 기타 시스템에 대한 별도의 배포판이 있습니다. 이 README.md파일은 런타임 아카이브(역사적 가치 혹은 장기 보존의 가치를 가진 기록이나 문서들의 컬렉션을 의미하며, 동시에 이러한 기록이나 문서들을 보관하는 장소, 시설, 기관 등을 의미)와 함께 제공됩니다. 런타임에 사용되는 문서, 구문 파일 및 기타 파일이 포함됩니다. Vim을 실행하려면 바이너리 아카이브 중 하나 또는 소스 아카이브 중 하나를 가져와야 합니다. 필요한 시스템은 실행하려는 시스템과 직접 컴파일해야 하는지 또는 직접 컴파일해야 하는지에 따라 다릅니다. 현재 사용 가능한 배포판에 대한 개요는 http://www.vim.org/download.php를 확인하십시오 .

최신 Vim을 구할 수 있는 인기있는 장소 :
	github에서 git 저장소를 확인하십시오.
	소스 코드를 아카이브로 가져옵니다.
	vim-win32-installer 저장소에서 Windows 실행 파일을 가져옵니다.

# 컴파일
바이너리 배포판을 얻은 경우 Vim을 컴파일 할 필요가 없습니다. 소스 배포판을 얻은 경우 Vim을 컴파일하는 데 필요한 모든 것이 src디렉토리에 있습니다. src/INSTALL지침을 참조하십시오 .

# 설치
시스템 별 지침은이 다음 파일 중 하나를 참조하십시오. READMEdir 디렉토리(저장소에 있음) 또는 최상위 디렉토리(아카이브를 압축 해제한 경우)에 있습니다.
README_ami.txt		Amiga
README_unix.txt		Unix
README_dos.txt		MS-DOS and MS-Windows
README_mac.txt		Macintosh
README_vms.txt		VMS
README_*.txt사용한 배포판에 따라 다른 파일 이 있습니다.

# 공식자료
Vim tutor는 초보자를 위한 1시간 교육 과정입니다. 종종 그것은 vimtutor로 시작할 수 있습니다. 자세한 내용은 :help tutor를 참조하십시오.

Vim에서 :help를 사용하는 것이 가장 좋습니다. 아직 실행 파일이 없으면 runtime/doc/help.txt. 를 읽으십시오. 다른 문서 파일에 대한 포인터가 들어 있습니다. 사용자 매뉴얼은 책처럼 읽히고 Vim 사용법을 배우는 것이 좋습니다. :help user-manual를 참조하십시오.

# 사자
Vim은 Charityware(우간다 기아 구제 프로그램 참여 조건)입니다. 원하는 만큼 사용하고 복사할 수 있지만 우간다에서 고아를 돕기 위해 기부하는 것이 좋습니다. 자세한 내용은 파일 runtime/doc/uganda.txt을 읽으십시오( :help uganda Vim 내부에서 수행).

라이센스 요약 : 수정되지 않은 Vim 사본을 사용하거나 배포하는 데 제한이 없습니다. Vim의 일부도 배포될 수 있지만 라이센스 텍스트는 항상 포함되어야 합니다. 수정된 버전의 경우 몇 가지 제한 사항이 적용됩니다. 라이센스는 GPL과 호환되며 Vim을 GPL 라이브러리로 컴파일하여 배포할 수 있습니다.

# 후원
버그 수정 및 새로운 기능 추가에는 많은 시간과 노력이 필요합니다. 작품에 대한 감사를 표하고 Bram과 다른 사람들이 Vim에서 계속 일하도록 동기를 부여하려면 기부금을 보내십시오.
Bram은 급여를 받는 직업으로 돌아왔으므로 이제 돈은 우간다의 어린이들을 돕기 위해 사용될 것입니다. runtime/doc/uganda.txt를 참조하십시오. 그러나 동시에 기부금은 Vim에서 계속 일하려는 Bram의 동기를 증가시킵니다!

스폰서에 대한 최신 정보는 Vim 웹 사이트를 참조하십시오 : http://www.vim.org/sponsor/

# 기여
Vim을 향상시키려면 CONTRIBUTING.md파일을 참조하십시오.

# 정보
Vim에 대한 최신 뉴스는 Vim 홈페이지(http://www.vim.org/)에서 찾을 수 있습니다. 문제가 있는 경우 Vim 설명서 또는 팁을 확인하십시오. 
http://www.vim.org/docs.php http://vim.wikia.com/wiki/Vim_Tips_Wiki
여전히 문제가 있거나 다른 질문이 있으면 메일 링리스트 중 하나를 사용하여 Vim 사용자 및 개발자와 상의하십시오. : http://www.vim.org/maillist.php

다른 방법이 없다면 버그를 직접 보고하십시오 : Bram Moolenaar Bram@vim.org

# 주요 저자
Bram Moolenaar Bram@vim.org : 기타 의견, 패치, 꽃 및 제안을 보내세요.
이것은 Vim 버전 8.1용의 README.md입니다. : Vi 개선

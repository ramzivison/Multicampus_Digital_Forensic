# Multicampus Digital Forensic

# 프로젝트 소개

MFT 로그를 활용하나 정보 유출 행위 탐지

# 프로젝트 목적

NFTS에 있어 가장 핵심적인 역할을 맡고 있는 MFT.
파일 크기, 작성 일자, 사용 권한, 데이터 내용 등, 파일에 관한 모든 정보가 MFT에 저장된다.
Endpoint의 MFT 로그 파일을 분석한다면, User가 정보 유출을 할 가능성이 있는지 없는지 확인할 수 있다고 생각한다.

# 프로젝트 개요

MFT 로그를 활용하나 정보 유출 행위 탐지

# 기획 배경

정보가 유출되었을 때 호스트에서 어떤 일이 발생했는지 알아내려면 NTFS 파일시스템에 대한 이해가 필수적이다.

NFTS에 있어 가장 핵심적인 역할을 맡고 있는 MFT. 파일 크기, 작성 일자, 사용 권한, 데이터 내용 등, 파일에 관한 모든 정보가 MFT에 저장된다. 
Endpoint의 MFT 로그 파일을 분석한다면, User가 정보 유출을 할 가능성이 있는지 없는지 확인할 수 있다.


# 기획 목표

MFT 로그 자동 분석 인공지능 개발

# 프로젝트 구조

    1. 사용 도구
    
    - VMWare - Windows 10 환경
    - FTK Imager -
    - analyzeMFT - 파이썬 코드 (fully parse the MFT file from an NTFS filesystem) 
    - HxD - Hex값으로 파일 여는 것
    
    2. 분석 경로
    
    
    3. 분석 대상
        - 필터 제작 (버튼 기능)
               - 아예 처음부터 거르거나 / 코드로 거르거나
               
        - windows 경로 제외
        
# 데이터 set 모음

# 한계 및 개선점

1. WinHex - demo 버전은 parsing 하는 데이터가 제한적이다. --> FTK Imager로 변경
2. analyzeMFT   - 날짜, 한글 인코딩이 깨졌다.
                - 불필요한 파일을 제외하는 필터하는 코드가 필요하다.


# 참고

# 협업 결과물 - WBS




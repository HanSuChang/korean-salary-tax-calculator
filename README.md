# korean-salary-tax-calculator
Practice project: Korean salary tax calculator with data validation and anomaly detection
# 연봉 실수령액 계산기

국세청 근로소득 간이세액표(tax.txt)를 기반으로  
연봉별 실수령액을 계산하는 파이썬 프로그램입니다.

## 주요 기능
- 연봉, 비과세 금액, 부양가족 수 입력
- 소득세 단조성 검증 및 이상치 자동 보정
- 월/연 실수령액 계산

## 실행 방법
1. Python 3.10 이상 필요
2. tax.txt 파일이 실행 파일과 같은 폴더에 있어야 함


python salary_calc.py


#실험결과
- 연봉 3,600만 ~ 1억 구간 테스트 완료
- 세금 단조성 검증 통과

> ⚠️ **주의**
>  
> 본 프로젝트는 **학습 및 연습 목적**으로 제작된 예제 프로그램입니다.  
> 실제 세금 신고, 급여 정산, 재무 판단에 사용하기에는 정확성을 보장하지 않습니다.
>  
> 계산 결과는 참고용으로만 활용하시고,  
>실제 세금 관련 사항은 국세청 또는 전문가의 공식 자료를 기준으로 확인하시기 바랍니다.


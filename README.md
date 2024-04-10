# grade calculator

1. **기간 : 2024.04.09** 

2. **기술스택**
    1. 개발언어 : java
    2. IDE : Intellij
 
3. **내용**
    1. mvc패턴 연습
    2. 학점계산기를 만든다. 평균 학점을 구해본다(sum(각과목평점*각과목학점)/총과목학점)

4. **파일설명(src/main/java/org.example.grade)**
    1. ../domain/Course  : 하나의 과목별로 과목명, 평점, 학점을 저장하는 클래스
    2. ../domain/Courses : (학생한명의)여러 과목들의 총 학점, 총 학점수*평점을 계산하는 클래스
    3. ../domain/Gradecalculator : 평균학점을 계산하는 클래스
    4. ../domain/GradeResult : 평균평점과 총학점을 저장하는 클래스
    5. ../ui/ConsoleOutput : 평균평점과 총학점을 프린트하는 클래스
    6. src/test/java/GradeCalculatorTest : 테스트 클래스
    
    


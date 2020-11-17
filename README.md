# sping_study
Spring FrameWork Study


# SQL문

- 조회 : SELECT * FROM table;
- 삽입 : INSERT INTO table(col1, col2, col3) VALUES(val1, val2, val3);
- 수정 : UPDATE table SET col = val WHERE col = val;
- 삭제 : DELETE FROM table WHERE = cond;

# 테이블
- 테이블 생성 : CREATE TABLE table (col1 type, col2 type);
- 테이블 삭제 : DROP TABLE table;
- 테이블 명 변경 : ALTER TABLE table RENAME table;


# 필드
- 필드 추가 : ALTER TABLE table ADD col INT;
- 필드 삭제 : ALTER TABLE table DROP col;
- 필드 수정 : ALTER TABLE table CHANGE col1, col2;
- 필드 타입 변경 : ALTER TABLE table MODIFY col INT;


# 백업
- mysqldump -u계정 -p비밀번호 데이터베이스명 > 백업파일명
mysqldump -uroot -pqweasd test > testdump.sql

# 복원
- mysql -u계정 -p비밀번호 데이터베이스명 < 백업파일명

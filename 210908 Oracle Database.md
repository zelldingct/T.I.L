# 1장 Oracle Database

210908

물리적 구조

* 데이터 파일
* 리두 로그 파일
* 컨트롤 파일

논리적 구조 

데이터 블록 < 익스텐트 < 세그먼트 < 테이블 스페이스

시스템 공유 영역(SGA) System Global Area
프로그램 공유 영역(PGA)

SHUTDOWN -> NOMOUNT -> MOUNT -> OPEN

SQL*PLUS - 기본적으로 제공되는 프로그램

TOAD - 대표적인 오라클 유틸리티

ORACLE SQL DEVELOPER - 오라클에서 제공하는 무료 유틸리티

WinSQL - 사용 잘 안함

CRUD

추가	Insert

삭제	Remove

검색	Select  

> 매우 중요하다. Oracle의 90%를 차지하고 있다고 해도 무방하다.

수정	Update

Oracle은 창고라고 상상하면 좋다. Data를 갖고 있는 상자

---

# 3장 SQL

SQL(Structured Query Language)

다른 종류의 범용 프로그래밍 언어로 작성된 프로그램(java 외 기타 등등)에 
내장 시킨 형태로도 사용 가능

DBMS(Data Base Management System)

구성

1. DDL(Data Definition Language)- CREATE DROP ALTER
2. DML(Data Manipulation Language)- INSERT DELETE UPDATE SELECT
3. DCL(Data Control Language)- GRANT REVOKE
4. 기타 구성요소
   * 트랜잭션 제어 - COMMIT(적용), ROLLBACK(취소)
   * 세션관리 - CONN, DISC
   * 제약조건 선언 - CONSTRAINT, CHECK, NOT NULL
   * 기타 - 주석, 힌트

---

# 4장

---




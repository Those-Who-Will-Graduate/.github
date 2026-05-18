## P!NKWARD

#### 1. Server
(1) `TailScale` IP 할당

(2) `requirements.txt` 만족하는 python 환경 구축 **(추가 필요)**

(3) 서버 구동
``` bash 
uvicorn server:app --host 0.0.0.0 --port 8000
```

#### 2. Frontend
(1) `frontend/` 디렉터리 이동

(2) `node.js` 환경 구축 후 확인
`````bash
node -v
npm -v
`````
`````
v18.0.0
9.0.0
`````

(3) `node.js` 패키지 설치
```bash
npm install
```

(4) `node.js` 구동
``` bash 
npm run dev 
```

#### 3. Embedded
(0) 작업 중 .. 

#### 4. AI
(1) `model/best.pt` 환경 구축 **수동 할당**

(2) `/detect` 할당 **연결 필요**


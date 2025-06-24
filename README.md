# -Daikibo-Machine-Health-Dashboard
This project simulates and visualizes the real-time health data of 9 machines across 4 factories (A–D). It was built to help Daikibo Industrials monitor:  🛠️ Temperature and vibration telemetry  🔴 Live alerts (OK, WARNING, ERROR)  📈 Historical trend analysis via charts  💾 Database persistence for future reports
Layer	Tech Used
Frontend	React.js, Recharts, Axios
Backend	FastAPI (Python), WebSocket API
Database	SQLite via SQLAlchemy ORM
Deployment	Localhost, production-ready APIs

cd backend
pip install -r requirements.txt

# Run server
uvicorn main:app --reload

 Visit: http://localhost:8000

✅ WebSocket: ws://localhost:8000/ws

✅ API: /history?machine_id=M7

cd frontend
npm install
npm start
✅ Visit: http://localhost:3000 (or 3001/3002)

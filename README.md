# บนเครื่อง
unzip /path/to/portfolio_app_demo.zip -d portfolio_app_demo
cd portfolio_app_demo
git init
git add .
git commit -m "Initial commit - Tum Portfolio AI demo"
# สร้าง repo บน GitHub ผ่านเว็บ แล้วคัดลอกคำสั่ง push ที่หน้า GitHub เช่น:
git remote add origin https://github.com/<yourname>/tum-portfolio-demo.git
git branch -M main
git push -u origin main

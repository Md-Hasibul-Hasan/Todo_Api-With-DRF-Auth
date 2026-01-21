<h1 align="center">🚀 DRF Auth & ToDo API</h1>

<p align="center">
  A Django Rest Framework project featuring Authentication and ToDo management.
</p>

<hr/>

<h2>🛠️ Requirements</h2>
<ul>
  <li>Python 3.8+</li>
  <li>pip</li>
  <li>Virtualenv (recommended)</li>
</ul>

<hr/>

<h2>⚙️ How to Run on Local Server</h2>

<h3>1️⃣ Navigate to Project Directory</h3>
<pre>
cd "ToDo_Api-With-DRF-Auth"
</pre>

<h3>2️⃣ Create Virtual Environment</h3>
<pre>
python -m venv .venv
</pre>

<h3>3️⃣ Activate Virtual Environment</h3>

<b>Windows</b>
<pre>
.venv\Scripts\activate
</pre>

<b>macOS / Linux</b>
<pre>
source .venv/bin/activate
</pre>

<h3>4️⃣ Install Dependencies</h3>
<pre>
pip install -r lib.txt
</pre>

<h3>5️⃣ Apply Database Migrations</h3>
<pre>
python manage.py makemigrations
python manage.py migrate
</pre>

<h3>6️⃣ Run Development Server</h3>
<pre>
python manage.py runserver
</pre>

<p>
  Server will start at:
  <br/>
  <b>http://127.0.0.1:8000/</b>
</p>

<hr/>

<h2>📘 API Documentation</h2>

<p>
  Use the Postman documentation below to explore all available endpoints,
  request formats, and responses.
</p>

<p>
  🔗 <a href="https://documenter.getpostman.com/view/48875561/2sBXViiWEw#a9abeb2a-092f-434f-8f2e-ba40436d1e5d" target="_blank">
  Postman API Documentation
  </a>
</p>

<hr/>

<h2>✅ Features</h2>
<ul>
  <li>User Authentication (Register / Login)</li>
  <li>JWT-based Authorization</li>
  <li>ToDo CRUD Operations</li>
  <li>RESTful API Design</li>
</ul>

<hr/>

<h2>👨‍💻 Author</h2>
<p>
  Developed with ❤️ using Django Rest Framework
</p>


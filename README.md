## Setup

```bash
git clone https://github.com/ppascha/mock-wordpress.git
cd mock-wordpress

cp .env.example .env

docker compose up -d

After containers start, open:

WordPress: http://localhost:8080
phpMyAdmin: http://localhost:8081

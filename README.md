docker build -t demo_nginx .
docker run --name=test_nginx -d -p 8000:80 demo_nginx
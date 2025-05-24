# login with psql inside container
psql -h postgres -U postgres -d postgres


# docker build for registry addon 
docker build -t yourusername/nginx-home:v1 .
docker push yourusername/nginx-home:v1

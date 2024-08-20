# Workshop
Repos to look at
- https://github.com/pgvector/pgvector
- https://github.com/pgvector/pgvector-python
- https://github.com/pgvector/pgvector-java
- https://github.com/pgvector/pgvector-go

Spin it up locally
```
docker run --expose 5432 --net=host --name pgvector -e POSTGRES_PASSWORD=mysecretpassword -d pgvector/pgvector:pg16
```

Connect with psql
```
psql -h 0.0.0.0 -U postgres
```

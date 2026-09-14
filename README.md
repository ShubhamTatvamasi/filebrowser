# filebrowser

```
docker run -d \
  --name filebrowser \
  -p 8080:80 \
  -v "$(pwd)/files:/srv" \
  -v "$(pwd)/filebrowser:/database" \
  --restart unless-stopped \
  filebrowser/filebrowser
```

http://localhost:8080

```bash
docker logs filebrowser
```

```
2026/09/14 16:13:12 User 'admin' initialized with randomly generated password: PXtj2J3XUGqo3VlN
```

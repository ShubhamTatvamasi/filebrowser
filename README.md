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

http://192.168.1.7:8080

```bash
docker logs filebrowser
```

```
2026/09/15 04:38:14 User 'admin' initialized with randomly generated password: -WlH5D6RyDhZVN2W
```

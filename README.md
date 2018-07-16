# PocketLobby.org

This site is the temporary home for Pocket Lobby. It's a simple brochure
site using a purchased template.

## Development

Start up a development server using Docker:

```bash
docker run -it --name pl-org -p 8080:80 -v $(pwd):/usr/local/apache2/htdocs/ httpd:2.4-alpine
```

Then open a browser to localhost:8080

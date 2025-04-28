# cloudflare-tunnel

## Getting Started

### Prerequisites

- [Docker](https://docs.docker.com/get-docker/)
- [Docker Compose](https://docs.docker.com/compose/install/)
- [Cloudflare Account](https://www.cloudflare.com/)
- [Cloudflare Tunnel](https://developers.cloudflare.com/cloudflare-one/connections/connect-application/tunnel/getting-started/)

```bash
docker compose up -d
```

### Configuration

- Create a `.env` file in the root directory of the project.
- Copy the contents of `.env.example` to `.env`.
- Fill in the required values in the `.env` file.
- Make sure to set the `TUNNEL_TOKEN` variable with the token generated from Cloudflare Tunnel.

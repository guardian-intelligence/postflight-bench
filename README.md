# postflight-bench

Wall-clock benchmark of a real-world Next.js CI job (cal.com @ pinned SHA:
install + prisma generate + type-check + unit tests) across runner lanes.
Dispatch `bench.yml` with a lane. Results are read from the Actions API.

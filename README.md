## What
A prompt based image generator [website](https://stable-diffusion-nextjs-alpha.vercel.app/)

<img src="https://github.com/hangjoni/stable-diffusion-nextjs/blob/7453fa0f0e75a35793e9cfda3a9220a7e5780d0e/image.png" width="350">

## How 
- Model: Stable Diffusion
- Model deployment: Replicate
- Web host: Vercel

## Learnings
`vercel environment variables not working` issues:
- Renaming REPLICATE_API_TOKEN to NEXT_PUBLIC_REPLICATE_API_TOKEN
- Then redeployed the app
- If the above still doesn't work, check back after a while as the issue might be intermittent due to Vercel cache

Useful links discussing this issue
[Vercel not supporting environment variable](https://github.com/orgs/vercel/discussions/1338#discussioncomment-4692590)
[Similar discussion](https://github.com/vercel/vercel/discussions/5015)

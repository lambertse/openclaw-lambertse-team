# TOOLS.md - Pixel's Tool Notes

## Image Generation

- **Provider:** fal.ai
- **API Key env var:** `FAL_KEY`
- **Skill:** `skills/fal-image-gen/SKILL.md`
- **Preferred model:** `fal-ai/flux/dev` (high quality, fast)
- **Fallback model:** `fal-ai/stable-diffusion-v3-medium`

## Output

- Save all generated images to `output/` directory
- Filename format: `YYYY-MM-DD-<slug>.png`
- Blog-ready size: `1920x1080` (landscape) or `1200x630` (OG image)

## Style Defaults

- Style: flat cartoon illustration, bold outlines, minimal background
- Negative prompt: photorealistic, 3D render, blurry, low quality, watermark

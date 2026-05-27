# Changelog

## 2026-05-27

- Fixed captcha modal detection when the Tencent captcha appears far to the left
  in wide browser windows. The backend now accepts left-side modal candidates
  while keeping the existing width and frequency filters.
- Verified the fix with a 1942x1042 Chrome capture where the captcha image was
  detected and recognized successfully.

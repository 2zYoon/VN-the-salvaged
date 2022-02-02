# Script
## keys
- `choice`: number of choice (default: [])
- `bg`: background image code
- `bgm`: BGM (repeat)
  - `none`: no BGM
  - `soundname`: some sound
- `speaker`: speaker
  - `none`: no speaker
- `sound`: sound (once)
  - `none`: no sound
  - `soundname`: some sound
- `color`: color (r, g, b, a)
- `dialog`: option for dialog (default: 1(enabled))
- `text[1-2]`: n-th line dialog text 
- `next`: code of next script (default: [cur+1])
- `bg-fadein`: background fade in (default: 1(enabled))
- `auto-branch`: auto-branch based on specific score (`"score": [key, threshold, if, else]`)
- `comment`: just a comment.

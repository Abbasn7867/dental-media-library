# Dental Clinic Media Library

Playbook, production chart and finished creatives for the video generation team: one uniform dental clinic (rooms, furniture, lighting, uniforms) and the AISC AI agent team (Annie, Sarah, Claire, Paula, Fiona, Emily, David, Megan).

## What's in here

| Path | What it is |
|---|---|
| `index.html` | The playbook. Open it in a browser: every file has an ID (A001–A173) in production order, with its exact file name, the reference images to attach, and the combined prompt. |
| `Dental_Clinic_Media_Library_Manifest.csv` | The chart: one row per image or clip, with file name, description, where it's used in the video, attach list, prompt and negative prompt. Feed this to the video tool. |
| `Creatives/` | Every finished image and clip, named exactly as `file_name` in the chart. The playbook previews this folder. |
| `assets/` | The two master reference frames shown at the top of the playbook. |

## How to add a new creative

1. In the playbook, use the **Next** button (bottom left) to find the next ID to make.
2. Attach the images listed under **Attach first**, press **Combine**, and paste the combined prompt into the image tool.
3. Save the result into `Creatives/` with the exact **Save as** name, then commit and push.

Open `index.html` from a local clone (or serve the folder with `python3 -m http.server`) and the playbook shows new files in `Creatives/` within 10 seconds, without a reload.

## Rules that never change

- Walls seafoam/aqua, light oak wood, white fixtures, teal upholstery, soft daylight.
- Every computer and wall screen is switched off (glossy black).
- Medium and detail plates must be clearly closer than the wide plate of the same room. If the tool won't do it, crop from the approved wide plate.
- Never redraw the AISC logo: attach `REF-10` (light backgrounds) or `REF-11` (dark backgrounds) as supplied.

Internal use only. All people shown are AI-generated characters.

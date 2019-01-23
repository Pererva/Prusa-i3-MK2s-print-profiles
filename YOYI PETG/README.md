# YOYI PETG

## Tested products
- PETG001-Transp Red : 1.75 mm, Semi-transparent Red

## Found problems:
* Self-dripping from nozzle when heated (very liquid)
  * Sometimes caused drops on tip - results in wrong 0-leveling and, potentially, bad adhesion
  * Make sure to clean the tip before printing!
* Terrible first layer adhesion (solvable)


## First layer adhesion solution
### 1. Polyimide Tape (works the best for me)
While bed is still cold:
1. clean the surface of printing bed
2. apply the polyimide tape and do not touch the surface after applying!
  - if touched - clean tape surface with IPA
3. print.

Printed part can be easily detached from tape while tape will be still adhered to bed.
This tape is usually used by electronics hobbyists to isolate conductive parts, which can self-heat. Material is also known as capron.

### 2. Hair Spray (for now - not tested)
Apply when bed is not heated:
- clean the surface with isopropyl alcohol to remove any residual from previous prints
- Cover with 1-2 uniform layers of spray
- print with brims

### 3. Glue stick (tested, works terribly, mostly - doesn't work!)
Apply when bed is not heated:
- clean the surface with isopropyl alcohol to remove any residual from previous prints
- treat the surface with glue stick (very thin layer)
- print with brims

## Post-print cleaning of bed
- If polyimide tape was used : let it cool down, remove the tape and clean the surface with IPA
- If Hair spray or glue stick was used : let it cool down, remove any residuals with IPA


# Method origin
Method is based on instructions from [methods collection by eoprede](https://github.com/eoprede/prusa_profiles/tree/master/MK2/Slic3r), with some adjustment for higher strength based on following videos by [YouTube channel CNC Kitchen](https://www.youtube.com/channel/UCiczXOhGpvoQGhOL16EZiTg):
https://www.youtube.com/watch?v=AmEaNAwFSfI
https://www.youtube.com/watch?v=upELI0HmzHc

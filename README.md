# Icons for tracks and exercises on Exercism

This repository contains the icons for language tracks and individual exercises on the new version of Exercism.

Many icons have been licenced from Noun Project. All of these have been licenced for use without attribution under Noun Project's Royalty Free model.

Copyrights are held by either Exercism or Noun Project, and released under the terms of [CC BY 3.0](https://creativecommons.org/licenses/by/3.0/). Attribution should be to both Exercism and Noun Project.

## Adding a new track icon

### Maintainers

Create an issue with links to the language and any information on standard/official logos. The design team will then create an icon.

### Website team

- Put the new logos provided by the design team into `tracks/logos`. They should match the track slug, should be pngs, and one should be suffixed wth `-t`.
- The `convert_track_images.sh` script does the magic of creating the variants.
- The last line of that script syncs with AWS, and will fail if you don't have the right keys/profile set up. New images can be manually added via the AWS console instead. Look at the last line for the paths etc. A `git diff` will show which files have been added by the script.

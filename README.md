# IDS721_Mini1_Zola_Website




[![pipeline status](https://gitlab.com/xw263/ids721_mini1_zola_website/badges/main/pipeline.svg)](https://gitlab.com/xw263/ids721_mini1_zola_website/-/commits/main)

## Purpose
The goal of this project is to create a portfolo page for using Zola.

## Preparations
### Create Zola Website
1. Install Zola-- `brew install zola`
2. Create website with `zola init`
3. Remove the theme came with the blank project `rmdir themes`
4. Find a theme on Zola website
5. Add a theme for css cd themes then `git submodule add` <theme name>
6. Create and modify pages in the content folder
7. `zola serve` to test website or zola build

### Deploy the Website
1. Install Vercel CLI `brew install node`,  `brew install vercel-cli`
2. Login to Vercel with `vercel login`
3. Link your repo with `vercel link`
4. Copy your `Vercel token`, `Vercel team id`, and `Vercel Org id` to Gitlab secrets (no quotation mark for the value)
5. Push repo to run pipeline filr .gitlab-ci.yml

## Reference
1. https://gitlab.com/jeremymtan/jeremytan_ids721_week1
2. https://www.getzola.org/themes/kita/
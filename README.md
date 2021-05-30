### Hi there 👋

name: Stefan Stax | Profile Readme

<!--START_SECTION:waka-->
on:
  schedule:
    # Runs at 12am IST
    - cron: '30 18 * * *'
  workflow_dispatch:
jobs:
  update-readme:
    name: Update Readme with Metrics
    runs-on: ubuntu-latest
    steps:
      - uses: staxstefan/README.MD@master
        with:
          WAKATIME_API_KEY: ${{ 9a2065e5-f160-4545-8c37-9730b48a41ea }}
          GH_TOKEN: ${{ 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 }}
          SHOW_TITLE: true
          SHOW_SHORT_INFO: true
          SHOW_IS: true
          SHOW_PROJECTS: true
          SHOW_COMMIT: true
          SHOW_DAY_OF_WEEK: true
          SHOW_LANGUAGE: true
          
          
<!--END_SECTION:waka-->

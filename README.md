# rancher-turtles-qa

POC rancher turtles QA, tests will be moved to an official repo.

What tests are doing:
1. Create the infra stack ( GCP runner, cert-manager, rancher )
2. Install the Turtles operator (embedded tar file for now, we will have to find a solution to build it locally)
3. Deploy the Turtles UI extension
4. Test the Turtles menu

I would like to automate this demo: https://www.youtube.com/watch?v=lGsr7KfBjgU&t=7s

[![UI-RM_head_2.7](https://github.com/juadk/rancher-turtles-qa/actions/workflows/ui-rm_head_2.7.yaml/badge.svg?branch=main)](https://github.com/juadk/rancher-turtles-qa/actions/workflows/ui-rm_head_2.7.yaml)

[![UI-RM_head_2.8](https://github.com/juadk/rancher-turtles-qa/actions/workflows/ui-rm_head_2.8.yaml/badge.svg?branch=main)](https://github.com/juadk/rancher-turtles-qa/actions/workflows/ui-rm_head_2.8.yaml)

# tolokapizza
Toloka API and Toloka Kit snippets

Toloka Kit Docs: https://toloka.ai/en/docs/toloka-kit/

Toloka API: https://toloka.ai/docs/api/

All snippets are implemented in Google Colab. It's just a playground for custom logic scripts.  Only god knows how they'll work 🙂

tolokaapi/ folder includes snippets implemented with the help of requests and json modules:

- GET exif data from photos and check the location on Google maps
- GET attachments from data collection project and send them to Cloud storage to get direct links for the verification project
- POST bonuses to a group of users. The amount depends on the quantity of submitted assignments
- GET all assignments from pool and save them to json file (with length parameter)
- POST general tasks to a production pool (with aiohttp)
- GET assignments without the ones from banned/suspended performers
- Transfer a project with pools (both regular and trainings) to another account (prod to prod)

tolokakit/ folder - with the help of Toloka Kit lib

- GET only control tasks answers from a pool
- GET specific output field values
- Write aggregation results to a TSV file (async)
- Download attachments together with input data
- Upload tasks to a pool
- Save accepted assignments from pool to tsv file
- Accepted assignments observer with log file
- Crop images from accepted assignments by bboxes

# tolokapizza
Toloka API and Toloka Kit snippets

Toloka Kit docs: https://toloka.ai/en/docs/toloka-kit/

Toloka API: https://toloka.ai/docs/api/

All snippets are implemented in Google Colab. It's just a playground for custom logic scripts.

tolokaapi/ folder includes snippets implemented with the help of requests and json modules:

- GET exif data from photos and check the location on Google maps
- GET attachments from data collection project and send them to Cloud storage to get direct links for the verification project
- POST bonuses to a group of users. The amount depends on the quantity of submitted assignments

tolokakit/ folder - with the help of Toloka Kit lib

- GET only control tasks answers from a pool
- GET specific output field values
- Write aggregation results to a TSV file (async)
- Download attachments together with input data
- Upload tasks to a pool

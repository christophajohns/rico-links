# RICO<sub>links</sub> Dataset

This repository contains the dataset that was used for the research described
in the Aalto University master thesis "Predicting Links for Mobile GUI Prototyping"
by Christoph A. Johns at Deutsches Forschungszentrum für Künstliche Intelligenz GmbH
(DFKI) Standort ​Niedersachsen.

## Data Format

| Feature Name         | Type   | Content                            |
| -------------------- | ------ | ---------------------------------- |
| source_screen_id     | string | refer to the original RICO dataset |
| source_element_id    | string | refer to the original RICO dataset |
| target_screen_id     | string | refer to the original RICO dataset |
| application_name     | string | refer to the original RICO dataset |
| interaction_trace_id | string | refer to the original RICO dataset |
| data_type            | string | 'link'/'non-source'/'non-target'   |
| split                | string | 'train'/'test'                     |

This dataset contains 56,790 examples.

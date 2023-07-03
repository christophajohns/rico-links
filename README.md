# RICO<sub>links</sub> Dataset

This repository contains the dataset that was used for the research described
in "Interactive Link Prediction as a Downstream Task for Foundational GUI Understanding Models" by [Christoph A. Johns](mailto:christophjohns@aalto.fi?subject=[GitHub]%20Suggested%20Links%Figma%Plugin) at Aarhus University.
The project was supervised by Michael Barz at German Research Center for Artificial Intelligence (DFKI).

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

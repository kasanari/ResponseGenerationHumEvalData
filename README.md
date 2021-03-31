# ResponseGenerationHumEvalData

This is an SQLite file containing all the human evaluation data.

## Views

* averages - Model variations, input description, output utterances and the respective average evaluation scores.
* instances - Model variations, input description and output utterances
* combined_s2_s3 - Combined table of stage 2 and 3 ratings.

## Tables

* options - Unique combinations of model variations, input and output.
* bleu - Bleu scores for options
* stage_2 - Typicality, offensiveness and forwardness ratings.
* stage_3 - Affect ratings.
* human_evals - Ratings from original human evaluation done on human-written lines.
  * Human written lines have been omitted as the RDG-Map dataset is not yet public.
* scenarios - Unique scenario descriptions and affect.
* utterances - Unique utterances produced by models.
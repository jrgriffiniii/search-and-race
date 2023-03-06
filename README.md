# Search and Race in the Library Catalog

## Search and Race Task Group for the [Princeton University Library](https://github.com/pulibrary)

### Sentiment Analysis

Currently, a strategy for offsetting bias implicit within the catalog records
which has been proposed has been to utilize a sentiment analysis model for
existing catalog records (which have been exported from the [Orangelight](https://github.com/pulibrary/orangelight) project).

#### PyTorch

The implementation for the sentiment analysis model uses Python along with the [PyTorch](https://github.com/pytorch) deep learning framework.

#### Google Colab

For the purposes of providing an interactive development environment for PyTorch, [Google Colab](https://colab.research.google.com) has been utilized exclusively for advancing the implementation and refinement of the sentiment analysis model.

#### HuggingFace

As the training and testing data sets must be publicly available in order to ensure that these efforts are transparent (as well as readily reproducible), [HuggingFace](https://huggingface.co/spaces/jrgriffiniii/search-and-race) shall also be utilized in order to publish the custom data sets used in support of these labors. Currently, these data sets are forthcoming.

### [Blacklight](https://github.com/projectblacklight/blacklight) Application

This serves as a customization of [Blacklight](https://github.com/projectblacklight/blacklight) in order to demonstrate a strategy for supporting efforts to offset and neutralize search result rankings for library catalog records containing terms which are specific to race, ethnicity, gender, sexual orientation, as well as those who have endured systemic and institutional oppression.

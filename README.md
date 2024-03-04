# Stock-Market-Sentiment-Analysis

This project utilizes Natural Language Processing (NLP) techniques, specifically VADER Sentiment Analysis, to predict the behavior of Indian Market Indices with significant accuracy. The model is trained on a dataset containing news headlines and corresponding stock index details.

## Dataset Details

The dataset comprises two main files:

1. **News**: Contains columns for Date, Title (Headline), and Description.
2. **Index details**: Includes columns for Date, Value (prices): Opening, High, Low, Closing, and a label to indicate gain/loss for that day.

The dataset used here pertains to the NIFTY50 index of the Indian Stock Market.

## Testing the Project

To test the project:

1. Download the `.ipynb` file and run it on Colab.
2. Upload the dataset files provided in this repository (an alternate dataset for the Dow Jones index is also available).
3. Run all the cells sequentially.

## Requirements

Ensure you have the following Python libraries installed:

- `pandas`
- `numpy`
- `nltk`

## Contributions

Contributions to this project are welcome! If you have suggestions for improvements or find any issues, please feel free to open an issue or submit a pull request.

## License

This project is licensed under the [MIT License](LICENSE).

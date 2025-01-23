# App Rating Prediction

## Description

**Objective**: The goal of this project is to build a model that predicts app ratings based on various features provided in the dataset.

### Problem Statement

The Google Play Store team is planning to launch a new feature where certain promising apps are boosted in visibility. This boost will manifest in various ways, including:

- Higher priority in recommendation sections such as "Similar apps", "You might also like", and "New and updated games".
- Increased visibility in search results.

This feature aims to give more attention to newer apps that show potential. To help with this process, we need to predict which apps are likely to have high ratings, as app ratings are a great indicator of an app’s quality and appeal.

### Domain

- **General**

### Dataset: Google Play Store Data

The dataset used for this project is called **googleplaystore.csv** and contains various features related to the apps available on the Google Play Store. The following are the fields included in the dataset:

| Feature          | Description                                                                 |
|------------------|-----------------------------------------------------------------------------|
| **App**          | Name of the application                                                     |
| **Category**     | The category to which the app belongs                                        |
| **Rating**       | Overall user rating of the app (target variable)                            |
| **Reviews**      | Number of user reviews for the app                                          |
| **Size**         | Size of the app                                                              |
| **Installs**     | Number of downloads/installs for the app                                    |
| **Type**         | Whether the app is **Paid** or **Free**                                      |
| **Price**        | The price of the app (if paid)                                               |
| **Content Rating** | The age group the app is targeted at (Children, Mature 21+, Adult)         |
| **Genres**       | Multiple genres the app can belong to (e.g., Music, Game, Family)            |
| **Last Updated** | Date when the app was last updated                                          |
| **Current Ver**  | Current version of the app available on Play Store                          |
| **Android Ver**  | Minimum required Android version for the app                                |

### Expected Outcome

The project aims to develop a model that predicts which apps will have higher ratings based on the available features. This will help identify promising apps that could be boosted by Google Play Store for better visibility and more downloads.

---

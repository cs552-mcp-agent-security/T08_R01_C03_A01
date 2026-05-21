# Engineered features in chapter 02

This page summarises the features the chapter-02 pipeline derives from the
raw California housing data.

| Engineered column | Derivation |
|-------------------|-----------|
| `rooms_per_household` | `total_rooms / households` |
| `bedrooms_per_room` | `total_bedrooms / total_rooms` |
| `population_per_household` | `population / households` |
| log-transformed columns | applied to skewed numerics (`total_rooms`, `total_bedrooms`, `population`, `households`, `median_income`) |
| `ocean_proximity_*` | one-hot encoding of the categorical column |
| `cluster_similarity_k` | RBF-kernel similarity to each of K geographic cluster centroids (notebook's custom transformer) |

Refer to the notebook for the canonical cell ordering.

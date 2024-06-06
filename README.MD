# Leaderboard

## Data Format

Please follow this example.

```shell
"GPT-3.5-Turbo (Nov 2023)": {
    "link": "https://openai.com/blog/new-models-and-developer-products-announced-at-devday",
    "open-data": "NONE",
    "overall": {
      "line": 96.27,
      "branch": 93.65
    },
    "overall@k": {
      "line": {
        "1": 88.35,
        "2": 90.02,
        "5": 92.14
      },
      "branch": {
        "1": 81.87,
        "2": 84.32,
        "5": 87.55
      }
    },
    "target": {
      "line": 67.76,
      "branch": 70.40
    },
    "prompted": true,
    "size": null
  },
```
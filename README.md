# 30_day_map_challenge

This repo tracks maps for the [30 day map challenge](https://30daymapchallenge.com/).

Feel free to get involved and submit pull requests if you would like to contribute.

## How to run notebooks

You should be able to install the required project dependencies and run all of the notebooks in this repository on your local machine.

Here's how to get setup with `uv` for example (similar setup instructions for other package managers):

* `uv pip install -f pyproject.toml`
* `uv run jupyter lab`

## How to contribute

Submit your notebooks with filenames like this: `day01_mp_points.ipynb`.  It should include this data:

* day of challenge in `dayXX` format
* your initials (e.g. `mp` for "max power")
* notebook description

Your notebook should output a map.

You should take a screenshot of your map and add it to the images folder.  Add a link to the map in your notebook.  Here's an example of the markdown:

```
![map](../images/day01_mp_points.png)
```

This enables others to view the map in GitHub without cloning the repo and running the notebook themselves.

## Datasets

When possible, just keep it simple and access data directly via HTTPS or S3, so it's easy for others to run your notebooks.

If that's not possible, include download instructions to your datasets.  Your notebook should be easily reproducible by other users.

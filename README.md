# Wikipedia based dataset (splits)

Custom Wikepdia dataset (splits) created using the tool from [repository](https://github.com/TJKlein/DataSplitCreator).

wiki_subset_1M_seed48.txt was created using:

```
python create_split.py --input_file_or_path wikipedia-en --split_samples 1000000
```

wiki_subset_1M_seed48_000.10percent_seed48.txt was created using:

```
python create_split.py --input_file_or_path https://media.githubusercontent.com/media/TJKlein/datasets/master/wiki_subset_1M_seed48.txt --split_percentage 0.1 --seed 48
```

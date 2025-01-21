# Labels

Label datasets for Farcaster users and casts created by the Warpcast client. For a comprehensive list of labels from all clients, see [farcaster/labels](https://github.com/farcaster/labels).


## Datasets

### [Spam](https://github.com/warpcast/backend/blob/main/spam.jsonl)

Labels indicating the relevance of user's casts to other users on the network. The `label_type` column is set to `spam`. The `label_value` column can take on the following values:
```
0 - Likely to be a spammy user or bot
1 - Likely relevant to followers only
2 - Likely to be broadly relevant
```



# Filter command

## Filter

| Feature | Notes |
| --- | --- |
exceptions | List exceptions.
uniqueexceptions | List all unique exceptions.

These are very basic proof-of-concept, *exceptions* will print all exceptions, while *uniqueexceptions* will list the first instance of each exception but skip duplicates. I'll be extending these as needed, in particular to cover cases where you need to work with a multi-GB logfile that contains misc daily operation entries intermixed with an Index Rebuild.

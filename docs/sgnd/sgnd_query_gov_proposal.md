## sgnd query gov proposal

Query details of a single proposal

### Synopsis

Query details for a proposal. You can find the
proposal-id by running "<appd> query gov proposals".

Example:
$ <appd> query gov proposal 1

```
sgnd query gov proposal [proposal-id] [flags]
```

### Options

```
      --height int   Use a specific height to query state at (this can error if the node is pruning state)
  -h, --help         help for proposal
```

### Options inherited from parent commands

```
      --chain-id string   The network chain ID
```

### SEE ALSO

* [sgnd query gov](sgnd_query_gov.md)	 - Querying commands for the governance module

###### Auto generated by spf13/cobra
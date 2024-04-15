# 删除单条数据

{% code fullWidth="true" %}
```sh
influx delete --bucket zz  --start '1970-01-01T00:00:00Z'  --stop $(date +"%Y-%m-%dT%H:%M:%SZ")  --predicate '_measurement="node_xfs_block_map_btree_records_inserted_total"' --org zdww --token 'wFhQd8mqJaWXi9QjGYurnAH1uZL-65TqnQ8_GhjCzSxCJpEr8u7zSdBnQjKrwWc_zPH5dV0HBwNRz4ye35cbKg=='

influx delete --bucket zz  --start '1970-01-01T00:00:00Z'  --stop $(date +"%Y-%m-%dT%H:%M:%SZ")  --predicate '_measurement="node_dmi_info"' --org zdww --token 'wFhQd8mqJaWXi9QjGYurnAH1uZL-65TqnQ8_GhjCzSxCJpEr8u7zSdBnQjKrwWc_zPH5dV0HBwNRz4ye35cbKg=='
```
{% endcode %}

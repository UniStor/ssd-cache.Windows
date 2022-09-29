# ssd-cache.Windows
sch: https://www.google.com/search?q=windows+ssd+cache guide: https://www.easeus.com/backup-recovery/ssd-cache.html https://www.partitionwizard.com/clone-disk/ssd-cache.html https://www.wepc.com/tips/ssd-cache/

# Type:
Which Type of SSD Caching is Best for You?
- Write-around SSD caching is best if you don’t want to flood your cache with data that you won’t be using very often. However, this leads to higher latency when loading the recognized “hot” data back to the cache.
- Write-back SSD caching is the fastest since it doesn’t have to wait for the underlying storage to complete. But even though this solves latency problems, the data will always be put at risk since power failure could corrupt the data.
- Write-through SSD caching is the most common type of caching today. Data is written both to the cache and the underlying storage at the same time and the write is only considered complete when it is written to your storage. This makes it the safest method, but also the slowest.

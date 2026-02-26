# Longest Subarray with Sum K

- Use prefix sum to track cumulative sum
- Store first occurrence of each prefix sum in a hash map
- If (current_sum - k) exists, update maximum length
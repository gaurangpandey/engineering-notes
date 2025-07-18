# Java Collections – Performance Notes

## ArrayList vs LinkedList
- ArrayList provides O(1) access but O(n) insertion in the middle
- LinkedList provides O(1) insertion but O(n) access

## HashMap vs TreeMap
- HashMap offers O(1) average time complexity
- TreeMap maintains sorted order with O(log n)

## When to use which
- Prefer ArrayList for read-heavy operations
- Use LinkedList only when frequent insertions/removals are required
- Use TreeMap only when sorted keys are necessary

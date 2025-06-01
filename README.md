# classes



# set 
# 📚 Python Set Methods & Use Cases

Python sets are **unordered collections** of **unique elements**. They support various methods to manipulate and query sets.

---

## 🔹 **Basic Set Operations**
| Operation | Description | Example |
| --------- | ----------- | ------- |
| `union()` | Returns a new set containing all unique elements from both sets. | `A.union(B)` or `A | B` |
| `intersection()` | Returns a new set with elements common to both sets. | `A.intersection(B)` or `A & B` |
| `difference()` | Returns a new set with elements in `A` but not in `B`. | `A.difference(B)` or `A - B` |
| `symmetric_difference()` | Returns a new set with elements in either `A` or `B`, but not in both. | `A.symmetric_difference(B)` or `A ^ B` |

---

## 🔸 **Set Methods**
| Method | Description |
| ------ | ----------- |
| `add(elem)` | Adds an element `elem` to the set. |
| `update(iterable)` | Adds multiple elements from an iterable (list, set, etc.) to the set. |
| `remove(elem)` | Removes `elem` from the set. Raises `KeyError` if not found. |
| `discard(elem)` | Removes `elem` if present. Does nothing if not found. |
| `pop()` | Removes and returns an arbitrary element. Raises `KeyError` if empty. |
| `clear()` | Removes all elements from the set. |
| `copy()` | Returns a shallow copy of the set. |
| `issubset(other)` | Checks if all elements of this set are in `other`. |
| `issuperset(other)` | Checks if this set contains all elements of `other`. |
| `isdisjoint(other)` | Checks if sets have no elements in common. |

---

## 🔹 **Set Creation & Characteristics**
- **Create a set**:  
  ```python
  my_set = {1, 2, 3}
  my_set = set([1, 2, 3, 3])  # Duplicates removed

#Day 31: Z algorithm
<br>
Z algorithm (Linear time pattern searching Algorithm)
This algorithm finds all occurrences of a pattern in a text in linear time. Let length of text be n and of pattern be m, then total time taken is O(m + n) with linear space complexity. Now we can see that both time and space complexity is same as KMP algorithm but this algorithm is Simpler to understand.
<br>

run

```
fn main(){
    let z = Z::new("baabaa");
    let matches = z.search("baa");
    assert_eq!(matches, [0,3]);
}
```

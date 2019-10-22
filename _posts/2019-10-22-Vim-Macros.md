---
layout: post
title: Vim Macros
description: Brief guide to using macros in vim
---


Modal key to initaite macro recording sequence.
```
q
```

This can be bound to any alphabetical key that you like.
```
<any_key>
<Key command sequence>
```

And then to end the recording:
```
q
```

To call the macro:
```
@q<key_recorded_to>
```

To call the macro repetitively:
```
<number>@q<key_recorded to>
```
eg:
````
50@qr
````

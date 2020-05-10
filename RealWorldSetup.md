## Real-world Experimental Setup

### Subject Systems

### Benchmarks

### Performance Measurements

### Manually Identified Change Points

#### LRZIP

| id  | hex                                      | message                                                                                                                      |
|-----|------------------------------------------|------------------------------------------------------------------------------------------------------------------------------|
| 521 | f792f72aa5086439c266433b39303c6377df909b | Use ffsl for a faster lesser_bitness function.                                                                               |
| 529 | 5edf8471d1eedf29ad2e477653062b3b7ca33c9e | Perform all checksumming in a separate thread to speed up the hash search in the rzip phase.                                 |
| 539 | f8d05b9a66fed0ab9fccc77fa2f99c476e4f8382 | Move zpaq compression to new libzpaq library back end.                                                                       |
| 628 | f378595dcec9bd7fdba88ecfb9818112a2b0887e | Make match_len a function completely removing all indirect calls to get_sb, significantly speeding up the single_get_sb case |
| 669 | 70bd5e9d3add335c67ea9535e6ea41af61edab3e | Allow less than maxram to be malloced for checksum to fix Failed to malloc ckbuf in hash_search2                             |
| 675 | 2086185ed58f8ccb2da7cae8c711195513df0919 | merge                                                                                                                        |
| 683 | 321c80f3822681d42e6ef0ec6d805a20fee1e659 | merge                                                                                                                        |
#### XZ

| id  | hex                                      | message                                                                                                                      |
|-----|------------------------------------------|------------------------------------------------------------------------------------------------------------------------------|
| 521 | f792f72aa5086439c266433b39303c6377df909b | Use ffsl for a faster lesser_bitness function.                                                                               |
| 529 | 5edf8471d1eedf29ad2e477653062b3b7ca33c9e | Perform all checksumming in a separate thread to speed up the hash search in the rzip phase.                                 |
| 539 | f8d05b9a66fed0ab9fccc77fa2f99c476e4f8382 | Move zpaq compression to new libzpaq library back end.                                                                       |
| 628 | f378595dcec9bd7fdba88ecfb9818112a2b0887e | Make match_len a function completely removing all indirect calls to get_sb, significantly speeding up the single_get_sb case |
| 669 | 70bd5e9d3add335c67ea9535e6ea41af61edab3e | Allow less than maxram to be malloced for checksum to fix Failed to malloc ckbuf in hash_search2                             |
| 675 | 2086185ed58f8ccb2da7cae8c711195513df0919 | merge                                                                                                                        |
| 683 | 321c80f3822681d42e6ef0ec6d805a20fee1e659 | merge                                                                                                                        |

#### OGGENC

| id  | hex                                      | message                                                                                                                      |
|-----|------------------------------------------|------------------------------------------------------------------------------------------------------------------------------|
| 521 | f792f72aa5086439c266433b39303c6377df909b | Use ffsl for a faster lesser_bitness function.                                                                               |
| 529 | 5edf8471d1eedf29ad2e477653062b3b7ca33c9e | Perform all checksumming in a separate thread to speed up the hash search in the rzip phase.                                 |
| 539 | f8d05b9a66fed0ab9fccc77fa2f99c476e4f8382 | Move zpaq compression to new libzpaq library back end.                                                                       |
| 628 | f378595dcec9bd7fdba88ecfb9818112a2b0887e | Make match_len a function completely removing all indirect calls to get_sb, significantly speeding up the single_get_sb case |
| 669 | 70bd5e9d3add335c67ea9535e6ea41af61edab3e | Allow less than maxram to be malloced for checksum to fix Failed to malloc ckbuf in hash_search2                             |
| 675 | 2086185ed58f8ccb2da7cae8c711195513df0919 | merge                                                                                                                        |
| 683 | 321c80f3822681d42e6ef0ec6d805a20fee1e659 | merge                                                                                                                        |

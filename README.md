# Tests-Unitaires

#### General's macros :
| Macros                     | Descriptions                                                                       |
| :------------------------- | :--------------------------------------------------------------------------------- |
| `cr_assert(condition)`     | Vérifie si la condition est vrai                                                   |
| `cr_assert_not(condition)` | Vérifie si la condition est fausse                                                 |
| `cr_assert_fail()`         | Force l'échec du test avec un message d'erreur par défaut                          |
| `cr_expect(condition)`     | Comme `cr_assert`, mais continue les tests même si la condition est mauvaise       |
| `cr_expect_not(condition)` | Comme `cr_assert_not`, mais continue les tests même si la condition est vraie      |
| `cr_expect_fail()`         | Comme `cr_assert_fail`, mais continue l'continue les tests                         |
| `cr_log_info(msg)`         | Affiche un message informatif dans le journal                                      |
| `cr_log_warn(msg)`         | Affiche un message d'avertissement dans le journal                                 |
| `cr_log_error(msg)`        | Affiche un message d'erreur dans le journal                                        |

#### Int's macros :
| Macros                     | Descriptions                                                                       |
| :------------------------- | :--------------------------------------------------------------------------------- |
| `cr_assert_eq(x, y)`       | Vérifie si x == y                                                                  |
| `cr_assert_neq(x, y)`      | Vérifie si x != y                                                                  |
| `cr_assert_lt(x, y)`       | Vérifie si x < y                                                                   |
| `cr_assert_leq(x, y)`      | Vérifie si x <= y                                                                  |
| `cr_assert_gt(x, y)`       | Vérifie si x > y                                                                   |
| `cr_assert_geq(x, y)`      | Vérifie si x >= y                                                                  |
| `cr_expect_eq(x, y)`       | Comme `cr_assert_eq`, mais continue les tests même si les valeurs sont différentes |
| `cr_expect_neq(x, y)`      | Comme `cr_assert_neq`, mais continue les tests même si les valeurs sont égales     |
| `cr_expect_lt(x, y)`       | Comme `cr_expect_lt`, mais continue les tests                                      |
| `cr_expect_leq(x, y)`      | Comme `cr_expect_leq`, mais continue les tests                                     |
| `cr_expect_gt(x, y)`       | Comme `cr_expect_gt`, mais continue les tests                                      |
| `cr_expect_geq(x, y)`      | Comme `cr_expect_geq`, mais continue les tests                                     |

#### Float's type :
| Macros                         | Descriptions                                                                       |
| :----------------------------- | :--------------------------------------------------------------------------------- |
| `cr_assert_float_eq(x, y, t)`  | Vérifie si x == y avec une tolérance t                                             |
| `cr_assert_float_neq(x, y, t)` | Vérifie si x != y avec une tolérance t                                             | 
| `cr_expect_float_eq(x, y, t)`  | Comme `cr_assert_float_eq`, mais continue les tests                                |
| `cr_expect_float_neq(x, y, t)` | Comme `cr_assert_float_neq`, mais continue les tests                               |

#### String's macros :
| Macros                               | Descriptions                                                                           |
| :----------------------------------- | :------------------------------------------------------------------------------------- |
| `cr_assert_str_empty(str)`           | Vérifie si str == NULL                                                                 |
| `cr_assert_str_not_empty(str)`       | Vérifie si str != NULL                                                                 |
| `cr_assert_str_eq(str1, str2)`       | Vérifie si str1 == str2                                                                |
| `cr_assert_str_neq(str1, str2)`      | Vérifie si str1 != str2                                                                |
| `cr_assert_str_lt(str1, str2)`       | Vérifie si lexicographiquement str1 < str2                                             |
| `cr_assert_str_leq(str1, str2)`      | Vérifie si lexicographiquement str1 <= str2                                            |
| `cr_assert_str_gt(str1, str2)`       | Vérifie si lexicographiquement str1 > str2                                             |
| `cr_assert_str_geq(str1, str2)`      | Vérifie si lexicographiquement str1 >= str2                                            |
| `cr_expect_str_eq(str1, str1)`       | Comme `cr_assert_str_eq`, mais continue les tests même si les valeurs sont différentes |
| `cr_expect_str_neq(str1, str2)`      | comme `cr_assert_str_neq`, mais continue les tests même si les valeurs sont égales     |

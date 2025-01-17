# Tests-Unitaires

- cr_assert(condition) => vérifie si la condition est vrai.
- cr_assert_not(condition) => vérifie si la condition est fausse.
- cr_expect(condition) => comme cr_assert, mais continue les tests même si la condition est mauvaise.
- cr_expect_not(condition) => comme cr_assert_not, mais continue les tests même si la condition est vraie.

- cr_assert_eq(x, y) => vérifie si x est égal à y.
- cr_assert_neq(x, y) => vérifie si x est différent de y.
- cr_asert_lt(x, y) => vérifie si x est strictement inférieur à y.
- cr_assert_leq(x, y) => vérifie si a est inférieur ou égal à y.
- cr_asert_gt(x, y) => vérifie si x est strictement supérieur à y.
- cr_assert_geq(x, y) => vérifie si a est supérieur ou égal à y.
- cr_expect_eq(x, y) => comme cr_assert_eq, mais continue les tests même si les valeurs sont différentes.
- cr_expect_neq(x, y) => comme cr_assert_neq, mais continue les tests même si les valeurs sont égales.

- cr_log_info(msg) => affiche un message informatif dans le journal.
- cr_log_warn(msg) => affiche un message d'avertissement dans le journal.
- cr_log_error(msg) => affiche un message d'erreur dans le journal.

Unit Tests on Criterion

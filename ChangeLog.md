# ChangeLog

## Unreleased
- NO CHANGE, switch to 2.1 because 2.0 is not up to date with master but procedure
  might not have been followed. - 2021-07-07 - 2.1.0

## 2.0

- FIX : Restreindre l'accès à `adminConges.php` aux utilisateurs ayant la permission « Modifier les paramètres globaux des congés » - 23/05/2022 - 2.0.6
- FIX : Déplacement de la ligne des compteurs : "Nombre de jour de récupération acquis" sur la partie N-1 - 13/12/2021 - 2.0.6
- FIX : v13 compat (NOTOKENRENEWAL, NOCSRFCHECK) - 2021-07-07 - 2.0.5

## 1.0

### New features

### Fixes

 - 1.3.7 Create absence for group menu disappeared
 - 1.3.6 Module setup UX improvement: use a `<select>` instead of a text input
   for the ID of the expense type to be accounted for during the luncheon voucher
   calculation.
 - 1.3.5 When calculating how many luncheon vouchers an employee is entitled to,
   take into account their expense reports from all active entities, not
   just from the current one [2021-03-02]

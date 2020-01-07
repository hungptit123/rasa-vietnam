## happy path 1
* accept
  - utter_accept
* thanh_toan_bankplus
  - utter_thanh_toan_bankplus
* goodbye
  - utter_goodbye

## happy path 2
* accept
  - utter_accept
* thanh_toan_qua_cua_hang
  - utter_thanh_toan_qua_cua_hang
* goodbye
  - utter_goodbye

## happy path 3
* accept
  - utter_accept
* thanh_toan_nap_the
  - utter_thanh_toan_nap_the
* goodbye
  - utter_goodbye

## happy path 4
* accept
  - utter_accept
* nang_han_muc
  - utter_nang_han_muc
* goodbye
  - utter_goodbye

## happy path 5
* accept
  - utter_accept
* nang_han_muc_truc_tiep
  - utter_nang_han_muc_truc_tiep
* ket_qua_nang_han_muc
  - utter_ket_qua_nang_han_muc
* goodbye
  - utter_goodbye

## sad path 1 
* accept
  - utter_accept
* thanh_toan_bankplus
  - utter_thanh_toan_bankplus
* thanh_toan_nap_the
  - utter_thanh_toan_nap_the
* nang_han_muc_truc_tiep
  - utter_nang_han_muc_truc_tiep
* ket_qua_nang_han_muc
  - utter_ket_qua_nang_han_muc
* goodbye
  - utter_goodbye

## sad path 2
* accept
  - utter_accept
* thanh_toan_bankplus
  - utter_thanh_toan_bankplus
* thanh_toan_nap_the
  - utter_thanh_toan_nap_the
* nang_han_muc_truc_tiep
  - utter_nang_han_muc_truc_tiep
* ket_qua_nang_han_muc
  - utter_ket_qua_nang_han_muc
* goodbye
  - utter_goodbye

## sad path 2
* accept
  - utter_accept
* thanh_toan_nap_the
  - utter_thanh_toan_nap_the
* nang_han_muc_truc_tiep
  - utter_nang_han_muc_truc_tiep
* ket_qua_nang_han_muc
  - utter_ket_qua_nang_han_muc
* thanh_toan_bankplus
  - utter_thanh_toan_bankplus
* goodbye
  - utter_goodbye

## sad path
* accept
  - utter_accept
* goodbye
  - utter_goodbye

## ket thuc 1
* goodbye
  - utter_goodbye

## ket thuc 3
* thanh_toan_nap_the
  - utter_thanh_toan_nap_the

## ket thuc 4
* nang_han_muc_truc_tiep
  - utter_nang_han_muc_truc_tiep
* ket_qua_nang_han_muc
  - utter_ket_qua_nang_han_muc

## ket thuc 5
* thanh_toan_bankplus
  - utter_thanh_toan_bankplus

## ket thuc 5
* khong_hieu
  - utter_khong_hieu

## fallback story
* out_of_scope
  - utter_boss_khong_hieu
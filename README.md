# 5G_BDA (5G Bidding Down Attack)
## Protocol flows
<p align="center">
  <img src="https://github.com/SitrakaResearchAndPOC/fork_5G_bda1/blob/main/5g_bda.jpg">
</p>
## code
*  OGS_5GMM_CAUSE_NO_NETWORK_SLICES_AVAILABLE in ogs_nas_5gmm_cause_t  and  uint8_t gmm_cause; in gmm_handle_service_request  at https://github.com/open5gs/open5gs/blob/main/src/amf/gmm-handler.c
*  bool nas::handle_service_request in https://github.com/srsran/srsRAN_4G/blob/release_20_04_2/srsepc/src/mme/nas.cc

## Documentations
* https://radix-security.com/files/2021_downgrade.pdf
* https://radix-security.com/research/5g-downgrade/
* https://www.techplayon.com/5g-nas-pdu-session-reject-cause-values-and-reasons/
* https://www.techplayon.com/5g-nas-registration-reject-cause/
* https://www.sharetechnote.com/html/5G/5G_Registration.html

* https://github.com/open5gs/open5gs/issues/1660
* https://github.com/open5gs/open5gs/commit/668cc59f94831c1369578e4feff000687ac7dfcc
* https://github.com/open5gs/open5gs/issues/1006
* https://open5gs.org/open5gs/docs/troubleshoot/01-simple-issues/

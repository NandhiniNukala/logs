  TXNNAME: PSO.ReqPay.DEBIT.PAY
      POJO: org.npci.pso.schema.ReqPay@3cb4a730
      RAW_REQUEST: <![CDATA[
<?xml version="1.0" encoding="UTF-8"?><ns2:ReqPay xmlns:ns2="http://npci.org/upi/schema/" xmlns:ns3="http://npci.org/cm/schema/"><Head msgId="5zvhPd0QCc4gVgdgHbi" orgId="NPC
I" prodType="PSO" ts="2025-06-16T17:25:57+05:30" ver="2.0"/><Meta/><Txn custRef="956776712786" id="SBI7aJWyEZlEwsNmaDLfJmTaONrqaBJKdeU" initiationMode="00" note="PAY" purpos
e="54" refId="0" refUrl="http://upi" subType="PAY" ts="2025-06-16T17:25:50" type="DEBIT"><RiskScores><Score provider="NPCI" type="TXNRISK" value="00999"/></RiskScores></Txn>
<Payer addr="14bvfBrUjjLrrfZTyBjoMtUdMxfwfweTq1@drsbi" code="0000" name="MR. QWFQWFQWF  QWFQWFQWF" seqNum="1" type="PERSON"><Info><Identity id="14bvfBrUjjLrrfZTyBjoMtUdMxfwf
weTq1" type="ACCOUNT" verifiedName="MR. QWFQWFQWF  QWFQWFQWF"/><Rating verifiedAddress="TRUE"/></Info><Device><Tag name="MOBILE" value="918655462548"/><Tag name="LOCATION" v
alue="19.0222,73.0170"/><Tag name="IP" value="192.168.2.34"/><Tag name="TYPE" value="Android"/><Tag name="ID" value="96c99729fa06faf8"/><Tag name="OS" value="Android"/><Tag
name="APP" value="org.npci.erupeeSBIUAT"/><Tag name="GEOCODE" value="19.0222,73.0170"/><Tag name="CAPABILITY" value="1"/></Device><Ac addrType="WALLET"><Detail name="ACTYPE"
 value="WALLET"/><Detail name="WALLETADDRESS" value="14bvfBrUjjLrrfZTyBjoMtUdMxfwfweTq1"/><Detail name="TSPID" value="159002"/></Ac><Creds><Cred subType="TPIN" type="PIN"><D
ata code="159002" ki="25102024">EB2wboDP/zQDLZ8DIwM9pp/bZ7wFUNUgN+W9dTz/AASDeZHEqmsvydN4gV6C3LPIblwfCsEjkYIEftNsn1nroF/FbWdDJUU5rWuibl5f1XCJvF6qcfu2/Z37Kw6yUl3BxDIxoUCV8Amha
bwVW1zMZSViFyUl8HKm0B1GmUob71rC8O6yGm7+BgnfY7CaScOcPYjvuKhn0Oj6wduTtZlUMqTbt/ykqyxzWXsBS/pgWMdF8zEOFtMLF6qtV+xPknpeGxxIFOTnBsDewjl11NWVzNXPhbdsfaB3MpQV60r3A7642EdIYDlNJcujd+
WZp7JaSixUN+shpfq5pvnLzan/Rw==</Data></Cred><Cred type="PSO"><Data code="NPCI" ki="NA">5lQHErwBP0xL7+Sj1XxvvJyflwKqTfWTXnFmXhz+BXVmBga/JgG8+9f7QPz/AnrKwz4T46AL0jmJt93iC5SnYX
mLhr00onc8I6BOfRFKqBhiQ4GMJi/JndzT/o2XNYdaxDv+DD6juEVvPaCGT/vGLmTL8n1Yoe67akBMheJnHOklZwl2coTJfJ/auzPeA71WYEiZ2HPger/92KILSY4tJgV9yIBJ+Y29KtTDCHDgAdaJ++MGwKnRvVe5PnnnLIcdPkZ
2G9X7RXIqv4Ir8ZSDt9bpcu11bnzGQVMMz4+qs5t14z40RH2FOvre42zX58inxXLHBt50STEDNyU1uvCQ5llq/Qqk1aqgfrBJEboHrkaqvSSJPY6kBlRZJRgIDAEIPQOsMq+S4kZAkLSsgY9UKU9GTHx/5CEpgsi3wJRULOZ6x/ey6smwvT99APQ7E/N8XistFeltObvgP55X9H6iKVZN92EBghYiGBk1seF6g/jN1eIec6KIjFuUZEWRw8yc7KU2vuYt77cFR6fH2Rwt8w4NYimYB8KHyC6uKo2ZgZKHVom+//UjTS9Rik+9nCmb2J0gUqrL7hoa16lNdwahb4GhImDdVpx4Q+VmAVYkq/WdHTesn0FJr/MECjLyiPTuIrGaV+5G5KtAWb8Ap86z96NUTtEdwWJcFDt5nauhs1ADiufhdtJrbzHwypGOIASPQ2DgvVUe9jZrHv5xGqo/ddmQQd/rMjLnKMio/JQRvc3kyOoIzaWNtM1jWwwGnrXx4+Xdb4Q8kHfhS0Qsd4lL16n0GZqw8+BphvujytAUBdxt/w5uqbuSvj/siVQvxt664CJImPFZT26PDbKAEMK9U1+rvBi6t8eT4fWgQO3oGFFDfgb8vgBnG5l8Y8A9abc3CH9P3DeoQMgrVF6X03qD7QJozd+KPvxk+wZmkQ0Ck8mufQ6K2mQbP30MAaoDJzfbHfGMauFCirsgp0O080674rG0a4uDiDKivrX3lCU0faHWHUY5Z88I1OGthxpfymXwFVKaJiZECMGRQREkEK5QTj65Fx1VsKhz+AKTdh/lbRiWd+d9ExF4lsir/BBefln8NfS1tyFW50tKEXhHqiIJ/+WBIlYRLX0NpGnql1z61i2StdbzOrUJtThnlR1s2bBYofcVvor2h2uVcV7VUvHibIIdKGU8fcRbqnSgZQQIF+1G2XjmmV0yY0+3RjZ9LHRW/I/1AZ9KRsmX4U0JtNmjUXnVIDG2E+nJSkS6sqqMiuZdcsqNjxFMhACfqoMH151/10YU51cCYmX6AsnU/99FOpuYOO8c91ulA9Ejqm59dE1nfOLBO6RXPpLsNz58p4uoixGSEO/Gy0pQmFt1n5V1zw==</Data></Cred><Cred type="TokenSecret"><Data code="159002" ki="25102024">YRaAydl6DVgVdI5i3FJGncoxXu7sgfBjTOLSjTmb5Jonffse5iGRVfG2EkuMs+QhJOCthOXmCTHOiQ/yuLaw8uSs2LvUAsU3Nz/oU8unqhufsOQJOEC1/JFc+R3gs0i2E652ZMri1OoPwy/ar11lTsGdlOpMG/MjNDJuPwGiym0Qpsiq8jM715/cVNxWRfeo0gIA9tXpZPLh+NbUnET15LD4omF4DO2aaU/01+sl7g1agPMhmEeAjNr+d1QmNK4AzZ6UtQRlv7CQnlBVrTSXg4U1uvGghEa/F4v3BswOGPUalk2oL8tmMgT8d742QmWtCJ6eb7Vc7cB5GNSjRJOf/g==</Data></Cred></Creds><Amount curr="INR" value="1.00"/></Payer><Payees><Payee addr="1BDo8V1sieDt6oqm75K7mHtmmdopfrDib2@drsbi" code="0000" name="Nallamilli Yogeswarasriramareddy" seqNum="1" type="PERSON"><Ac addrType="WALLET"><Detail name="ACTYPE" value="WALLET"/><Detail name="TSPID" value="159002"/><Detail name="WALLETADDRESS" value="1BDo8V1sieDt6oqm75K7mHtmmdopfrDib2"/></Ac><Amount curr="INR" value="1.00"/></Payee></Payees><Signature xmlns="http://www.w3.org/2000/09/xmldsig#">{wiped}</Signature></ns2:ReqPay>
]]>
 API_SOURCE: {"name":"PSO"}
      INSTITUTE_CACHE: {"institution":{"id":1,"name":1,"shortCode":"SBICO","acquirerId":"159002"}}
      TXN_SCHEMA: {"use-txn-type":true,"clazz":"org.npci.pso.schema.ReqPay"}
      TXN_ID: SBI7aJWyEZlEwsNmaDLfJmTaONrqaBJKdeU
      PROFILER:
       <profiler>
         open [1.6/1.6]
         init-decrypt [464.9/466.6]
         decrypt.rsa.util [260.2/726.8]
         decrypt.RAW_MPIN [2.8/729.7]
         decrypt.TokenSecret [2.7/732.4]
         close [631.8/1364.3]
         end [3.0/1367.3]
       </profiler>

      TIMESTAMP: Mon Jun 16 17:25:57 IST 2025
      DB: DB{}
      LOGEVT:
        <info>
          SWITCH PSO.ReqPay.DEBIT.PAY (init-fin-api parse-fin-txn fetch-token-wallet check-rules parse-request-creds wallet-pin-validation handle-debit check-kcc-rule-abort-flow prepare-pay-response save-db select-pso-fin-endpoint route-to-endpoint close)

          (create-tranlog =>)
          Payer VPA : 14bvfBrUjjLrrfZTyBjoMtUdMxfwfweTq1@drsbi
          Flow : 000
          Populate Fin Tranlog
          ACNUM : null

          (ensure-lock(only-lock) =>)
          Lock Key .SBI7aJWyEZlEwsNmaDLfJmTaONrqaBJKdeU

          (check-duplicate(pso) =>)
          Check Duplicate : SBI7aJWyEZlEwsNmaDLfJmTaONrqaBJKdeU
          Duplicate Check PSO.ReqPay.DEBIT SBI7aJWyEZlEwsNmaDLfJmTaONrqaBJKdeU
          REFID =0 itc =,PSO.ReqPay.DEBIT, inst value =PSO.ReqAuthDetails.PAY,APP.ReqPay.LOAD

          (parse-fin-txn-details =>)

          (fetch-wallet =>)
          Wallet flow: DEBIT, direction: ONUS
          PSO.ReqPay.DEBIT PSO.ReqPay.DEBIT.PAY
          DEBIT
          ONUS
          false
          Load the Payee wallet : 1BDo8V1sieDt6oqm75K7mHtmmdopfrDib2
 <payee>{"id":14953,"name":"MR. USER3  QWFQWFQWF","email":null,"institute":1,"mobile":"918655693368","type":"CUSTODIAN","created":"2025-06-10 12:50:38.0","updated":"2025-06-16 13:56:48.0","status":"VERIFIED","created":"2025-06-10 12:50:38.0","updated":"2025-06-16 13:56:48.0","status":"VERIFIED","kycStatus":"FULL","pan":null,"walletAddress":"1BDo8V1sieDt6oqm75K7mHtmmdopfrDib2"}</payee>

          (check-cooling-period =>)
          setting default OS as Android for OS Based cooling period limit check.
          CUSTOMER MOBILE : 918655462548
          OS TYPE : Android
          2025-06-09 14:09:58.0, 86400, got : 616559

          (check-pcbdc-no-kyc-txn =>)
          pcbdc no-kyc check enabled

          (prepare-for-check =>)
          -5 full-kyc-per-txn-limit ACTIVE
          Rule    : -5 : full-kyc-per-txn-limit
          Profile : customer-mobile

          1 single_txn_10_sec ACTIVE
          2 basic-kyc-no-txn ACTIVE
          3 full_kyc_consolidated_credit ACTIVE
          4 full_kyc_consolidated_debit ACTIVE
          6 full_kyc_cooling_period_credit ACTIVE
          7 full_kyc_cooling_period_debit ACTIVE
          8 full-kyc-cooling-per-txn-limit ACTIVE
          9 no_kyc_consolidated_credit ACTIVE
          10 no_kyc_consolidated_debit ACTIVE
          12 pinless_full_kyc_per_txn ACTIVE
          13 full_kyc_pinless_consolidated_debit ACTIVE
          14 block_mobile ACTIVE
          15 block_device ACTIVE
          16 Bind Mobile Device ACTIVE
          17 full_kyc_pinless_cooling_consolidated_debit ACTIVE
          18 pinless_cooling_full_kyc_per_txn ACTIVE
          19 full_kyc_cooling_period_credit_ios ACTIVE
          20 full_kyc_cooling_period_debit_ios ACTIVE
          21 full_kyc_consolidated_redeem ACTIVE
          22 full_kyc_consolidated_monthly_transfer_limit ACTIVE
          23 full_kyc_consolidated_load_limit ACTIVE
          24 min_kyc_consolidated_credit ACTIVE
          25 min_kyc_consolidated_debit ACTIVE
          26 min-kyc-per-txn-limit ACTIVE
          Profile 'customer-mobile' not required to update for this txn.
          Validate Rule Summary
  Check full-kyc-per-txn-limit, in-flight : true
          {"id":-5,"name":"full-kyc-per-txn-limit","status":"ACTIVE"}
          {"type":"MAX","count":1,"amount":2000}
          Check Per Txn Settings {"type":"MAX","count":1,"amount":2000}
          Count check 1/1 : [OK]
          Amount Check 1.00/2000 : [OK]

          Update success (true) for All traces

          (parse-req-block =>)
          Putting key.PIN.TPIN : RAW_MPIN
          Putting key.PSO : PSO
          Putting key.TokenSecret : TokenSecret

          (decrypt-cred-block =>)

          Decrypt : RAW_MPIN
          Put : RAW_MPIN > RTSP_MPIN

          Decrypt : TokenSecret
          Put : TokenSecret > TokenSecret

          (decode-cl-blocks =>)
          Decode PSO : as PSO
          {"tokenData":{"useTokens":[{"qty":"1","tag":"eyJydWxlSWQiOlsiYWQ4ODAzYjAtOTljMC00MmVjLTk0ZWItMjQ5OTU1ODBkMTE2Il0sInRva2VuVHlwZSI6IlBDQkRDIn0=","den":"53.00"}],"loadTokens":[{"qty":"1","tag":"eyJydWxlSWQiOltdLCJ0b2tlblR5cGUiOiJQQ0JEQyJ9","den":"52.00"}]},"useTokens":[{"id":"b933451b184801f515b19c063f98001c83b7a6ad265056f22f766351703f1eaa","tag":"eyJpc3N1ZXJTaWduYXR1cmUiOiJtLzQ0Jy82MCcvMHxtLzQ0Jy82MCcvMjAnLzAvMHwweGI0YjU5YWQ2NThlOTg4M2QyZGNiNTQyMjBmMGEzNGQ3ZDY0NGYyNzY2YWI4ZTQwYjVkYzg4Zjc0YTc4ZWFjNDY3YmM3ODA5MGFjNmZmMTRiMDkwNDVkNGVmNmRmNGVhOGQwZGQ5OWM5YTEzODk1NTQ4ZDc3NGE4ZTU4ZjQxZjAzMDEiLCJjcmVhdGlvblRpbWVzdGFtcCI6IjIwMjUtMDYtMTJUMTU6MTE6MzMuMTAzWiIsImV4cGlyYXRpb25UaW1lc3RhbXAiOiIyMDMwLTA2LTA0VDE4OjI5OjU5Ljk5OVoiLCJjdXJyZW5jeSI6IklOUiIsIm93bmVyQWRkcmVzcyI6IjF8MHgyNjMyMEQyOTEzOTU5OGUwRTU3OWI1NDQ4OWI3RmYyZTQxYjI1MTY5IiwidG9rZW5UeXBlIjoiUENCREMiLCJydWxlSWQiOlsiYWQ4ODAzYjAtOTljMC00MmVjLTk0ZWItMjQ5OTU1ODBkMTE2Il0sImlzT2ZmbGluZVNwZW5kYWJsZSI6ImZhbHNlIn0=","value":"53.00","serialNo":"304154311791583"}]}
          SWITCH null (check-wallet-pin)

          (check-wallet-pin =>)

          (normalize-final-response =>)
          RC : null
          Check with Source+TXN Specific RC
          normalize : PSO.ReqPay.DEBIT.PAY, rc : null
          PSO.ReqPay.DEBIT.PAY.null :
          Check with Source Specific RC
          normalize : PSO, rc : null
PSO.null :
          normalize : PSO, rc : 9999
          PSO.9999 :
          Assign Default Failure RC
          SWITCH true (prepare-req-pay-vald select-validation-service-endpoint route-to-endpoint parse-validation-service-response check-kcc-rule)

          (pcbdc-validation-service =>)
          Validation service geoCode =19.0222,73.0170

          (set-pso-endpoint =>)
          SetTargetEndpoint : VALIDATION-SERVICE

          (prepare-xml =>)

          (sign-payload =>)
          Request Signing Skipped

          (secure-response =>)
          SWITCH DEFAULT (send-with-http)

          (query-http =>)
          Request Name :: ReqPay
          Headers => {x-olympic=joJFwcBPPl4MiYpLiQ4iGVWjIzkAsbRy, User-Agent=PostmanRuntime/7.28.4}
          URL => https://10.177.141.93/api/validation-service/v1/ReqPay
          Processing TXNNAME: PSO.ReqPay.DEBIT.PAY, Call VALIDATION-SERVICE, API ReqPay Type PBT
          Response : ResponseWrapper ~ {"status":200,"error":false,"body":"<token:RespPay xmlns:token=\"http:\/\/npci.org\/token\/schema\/\"><Head ver=\"2.0\" ts=\"2025-06-16T17:25:58+05:30\" orgId=\"159002\" msgId=\"5zvhPd0QCc4gVgdgHbi\" prodType=\"VALD\"><\/Head><Txn id=\"SBI7aJWyEZlEwsNmaDLfJmTaONrqaBJKdeU\" note=\"PAY\" custRef=\"\" refId=\"0\" refUrl=\"http:\/\/pso\" ts=\"2025-06-16T17:25:58+05:30\" type=\"PBT\" purpose=\"93\" initiationMode=\"\" refCategory=\"\" orgTxnId=\"\" subType=\"\" orgRespCode=\"\"><\/Txn><RespDetails result=\"FAILURE\" errCode=\"ERROR_INVALID_PCBDC_TRANSACTION\" msg=\"Validation of PBT failed because of one or more rule failures\"><Tokens><Token><Detail name=\"tokenID\" value=\"b933451b184801f515b19c063f98001c83b7a6ad265056f22f766351703f1eaa\"><\/Detail><Detail name=\"docType\" value=\"PBT\"><\/Detail><Detail name=\"status\" value=\"FAILURE\"><\/Detail><Detail name=\"errCodes\" value=\"ERROR_INVALID_MCC_CODE\"><\/Detail><\/Token><\/Tokens><\/RespDetails><\/token:RespPay>","body":null}
          Response           : 200

          (parse-rule-creation-response =>)

          (prepareForAbort:parse-token-validation-response =>)
          SWITCH null ()
          SWITCH DEBIT (handle-wallet-debit)
          SWITCH 54 ()
          SWITCH null ()

          (prepareForAbort:normalize-final-response =>)
          RC : pcbdc.token.validation.error
          Check with Source+TXN Specific RC
 normalize : PSO.ReqPay.DEBIT.PAY, rc : pcbdc.token.validation.error
          PSO.ReqPay.DEBIT.PAY.pcbdc.token.validation.error : Z08,PCBDC token validation failure
          Use RC : Z08,PCBDC token validation failure

          (prepareForAbort:prepare-resp-pay =>)
          Token Before1 msg :SBIV100011000000000000000000002e9ah
          Token Before2 msg :null
          Populated TARGET_POJO org.npci.pso.schema.RespPay

          (prepareForAbort:save-db(pso) =>)
          Committing DB Txn.

          (prepareForAbort:set-pso-endpoint =>)
          SetTargetEndpoint : PSO-FIN

          (prepareForAbort:prepare-xml =>)

          (prepareForAbort:sign-payload =>)
          Sign Payload to 'PSO-FIN' @ SBI Bank

          (prepareForAbort:secure-response =>)
          SWITCH DEFAULT (send-with-http)

          (prepareForAbort:query-http =>)
          Request Name :: RespPay
          Headers => {x-olympic=joJFwcBPPl4MiYpLiQ4iGVWjIzkAsbRy, User-Agent=PostmanRuntime/7.28.4}
          URL => https://10.177.141.54/olympic/pso/RespPay/2.0/urn:txnid:SBI7aJWyEZlEwsNmaDLfJmTaONrqaBJKdeU
          Processing TXNNAME: PSO.ReqPay.DEBIT.PAY, Call PSO-FIN, API RespPay Type DEBIT, RC pcbdc.token.validation.error
          Response : ResponseWrapper ~ {"status":200,"error":false,"body":"<?xml version=\"1.0\" encoding=\"UTF-8\" standalone=\"yes\"?><ns2:Ack xmlns:ns2=\"http:\/\/npci.org\/upi\/schema\/\" api=\"RespPay\" reqMsgId=\"5zvhPd0QCc4gVgdgHbi\" ts=\"2025-06-16T17:25:59+05:30\"\/>","body":null}
          Response           : 200
          Update Status : pcbdc.token.validation.error
          Transaction Details :com.sarvatra.rtsp.transaction.sre.RiskCheckTxnData@65d6d37

          <rule>{"id":-5,"name":"full-kyc-per-txn-limit","status":"ACTIVE"}</rule>

          (prepareForAbort:log-duration =>)

          (prepareForAbort:purge-async-cache =>)

          (abort:parse-rule-creation-response =>)

          (abort:validate-kcc-transaction =>)

          (abort:validate-kcc-transaction(abort flow) =>)
(abort:normalize-final-response =>)

          (abort:prepare-resp-pay =>)

          (abort:save-db(pso) =>)

          (abort:set-pso-endpoint =>)

          (abort:prepare-xml =>)

          (abort:sign-payload =>)

          (abort:secure-response =>)

          (abort:query-http =>)

          (abort:log-duration =>)

          (abort:clean-up =>)

          (abort:release-locks =>)

          (abort:queue-sms-notification =>)

          (abort:purge-async-cache =>)
          Processing POJO
          Processing USER_INFO
          Processing XML_REQUEST
          Processing FETCHED_CUSTOMER_ACCOUNTS
          Processing APP_CARD_DATA
          Processing TXN_FOLLOWUP
        </info>

      UID_CACHE: true
      AUTO_SWAP_CREDIT_METHOD: MERCHANT
      TXN_LEG_TYPE: DEBIT
      MSG_ID: SBIV100011000000000000000000002e9ah
      TXN_TYPE: DEBIT
      PURPOSE: 54
      CHECK_DUPLICATE: false
      USE_ACNUM:
      IS_ASYNC_REQUEST: true
SECURED_AES_KEY: ERZpJTtyTwnHi69L+NYo/rFaNj9mfdMn/UtUExBKTt4fr8pyKh8+gBPWnBZdPBrphM5bkDr/PfTTL5QN4M/+jhz7wWV9A4N0G77vwX7rRG+pO9ANzem0hVkPinzrwZK73btL1J+HV+ikxJEpK1ci8enape6L80ok0hYSdeqFOBfhjQGVIB8AGdfOBhHHRLv6BRh2O96+Me4W/G+3B02sHRXVwUroECi2bHRTd6/Ni7w6f6VRZ2Yn1OpPKKexDaDDBcHIgh1s1gDt+hgW/+x+KOG3TBJ4cBKEP6bL4tn88BbCljA60zQEXkJsF5wkQ8SNO9UG1Lim9/cSgzEep3gI9g==
      SECURED_INIT_VECTOR: KGsEXcqTokjYMupy6R1UH03daSHXp2U8UEKBO2VeTB+4TN7jYMuT2AxNlz5jt31Z5UNz5DZmLz12/wcLTHVI6BLAzMcSxHgXbOCsFnc2wvzsqD9gXiUnNSLFOI4U2PiWK7RWIkoogIuXGfzlISWZCEDna0FahBXWH+d97stvJZRXtlGRDtKXkU8b9RdAaV9vs7m933ZxOhzOFf6x+PYL0+z/b/1LCHXdQEEq9dkq4nvmm/fm9PwRq0GBJnwHnycyi1sAmxxR8GxUUMS341vfR2mKIjbxZcgP/YB7llTnigMS3P8/3Am7tSHPQqEHfeOxvGcKCCewylS6sdYLlmbNWA==
      TOKEN_TRANLOG: <![CDATA[
TokenFinancialTranlog[id=862529,itc=PSO.ReqPay.DEBIT,direction=ONUS,txnId=SBI7aJWyEZlEwsNmaDLfJmTaONrqaBJKdeU,msgId=SBIV100011000000000000000000002e9ah,type=DEBIT,status=VOID,approvalNumber=<null>,displayMessage=PCBDC token validation failure,irc=pcbdc.token.validation.error,currencyCode=INR,amount=1.00,rc=Z08,node=RTSP28,refNo=956776712786,subType=PAY,institute=1,date=Mon Jun 16 17:25:57 IST 2025,captureDate=Mon Jun 16 00:00:00 IST 2025,source=PSO,destination=<null>,cbsRefId=<null>,refId=0,payerVPA=14bvfBrUjjLrrfZTyBjoMtUdMxfwfweTq1@drsbi,paymentMode=<null>]
]]>

      PAYER_POJO: org.npci.token.schema.Payer@3b37acf9
      PAYEE_POJO: org.npci.token.schema.Payee@221a069b
      PAY_TYPE: DEBIT
      TXN_FLOW: DEBIT
      DIRECTION: ONUS
      TXN_USER: 14bvfBrUjjLrrfZTyBjoMtUdMxfwfweTq1@drsbi
      TRANLOG.MAIN: <![CDATA[
TokenFinancialTranlog[id=862528,itc=APP.ReqPay.PAY,direction=ONUS,txnId=SBI7aJWyEZlEwsNmaDLfJmTaONrqaBJKdeU,msgId=SBIV100011000000000000000000002e9ag,type=PAY,status=PENDING,approvalNumber=<null>,displayMessage=<null>,irc=<null>,currencyCode=INR,amount=1,rc=<null>,node=RTSP28,refNo=956776712786,subType=<null>,institute=1,date=2025-06-16 17:25:53.0,captureDate=2025-06-16 00:00:00.0,source=APP,destination=<null>,cbsRefId=<null>,refId=0,payerVPA=14bvfBrUjjLrrfZTyBjoMtUdMxfwfweTq1@drsbi,paymentMode=<null>]
]]>

      TOKEN_CUSTOMER_WALLET: {"id":14762,"name":"MR. QWFQWFQWF  QWFQWFQWF","email":null,"institute":1,"mobile":"918655462548","type":"CUSTODIAN","created":"2025-03-29 19:12:02.0","updated":"2025-06-09 14:09:58.0","status":"VERIFIED","created":"2025-03-29 19:12:02.0","updated":"2025-06-09 14:09:58.0","status":"VERIFIED","kycStatus":"FULL","pan":null,"walletAddress":"14bvfBrUjjLrrfZTyBjoMtUdMxfwfweTq1"}
      TOKEN_CUSTOMER_WALLET_PAYER: {"id":14762,"name":"MR. QWFQWFQWF  QWFQWFQWF","email":null,"institute":1,"mobile":"918655462548","type":"CUSTODIAN","created":"2025-03-29 19:12:02.0","updated":"2025-06-09 14:09:58.0","status":"VERIFIED","created":"2025-03-29 19:12:02.0","updated":"2025-06-09 14:09:58.0","status":"VERIFIED","kycStatus":"FULL","pan":null,"walletAddress":"14bvfBrUjjLrrfZTyBjoMtUdMxfwfweTq1"}
      TOKEN_CUSTOMER_WALLET_CHANNEL:
      KYC_STATUS: FULL
      CUSTOMER: {"id":15930,"name":"Nallamilli Yogeswarasriramareddy","email":null,"institute":1,"mobile":"918655462548","type":"CUSTODIAN","created":"2025-03-29 19:12:13.0","updated":"2025-06-09 14:07:34.0","status":"VERIFIED","device":{"id":16543,"deviceId":"96c99729fa06faf8","model":"24094RAD4I","os":"Android","pckage":"org.npci.erupeeSBIUAT","status":"VERIFIED","created":"2025-06-09 14:07:34.0","updated":null,"institute":1,"channel":null},"vpa":"14bvfBrUjjLrrfZTyBjoMtUdMxfwfweTq1@drsbi","kycStatus":"MIN","pan":null}
      TOKEN_HOLDER_PAYER: {"walletAddress":"14bvfBrUjjLrrfZTyBjoMtUdMxfwfweTq1","bankPoolWallet":false,"ourCustomer":true,"vpa":"14bvfBrUjjLrrfZTyBjoMtUdMxfwfweTq1@drsbi","name":"Nallamilli Yogeswarasriramareddy"}
      TOKEN_HOLDER_PAYEE: {"walletAddress":"1BDo8V1sieDt6oqm75K7mHtmmdopfrDib2","bankPoolWallet":false,"ourCustomer":true,"vpa":null,"name":"MR. USER3  QWFQWFQWF"}
      CUSTOMER_COOLING: false
      PINLESS_TXN: false
      PINLESS_TXN_COOLING: false
      OS: Android
P2P_TXN: true
      PCBDC_NO_KYC: false
      MOBILE: {wiped}
      TSP_TXN: PSO.ReqPay.DEBIT.ONUS.DEBIT.DEBIT
      c.s.r.t.RiskTxnSupport$SRE.TXN_DETAILS: com.sarvatra.rtsp.transaction.sre.RiskCheckTxnData@65d6d37
      c.s.r.t.RiskTxnSupport$SRE.SCHEMA: com.sarvatra.re.schema.RiskEngineConfiguration@7eff727a
      c.s.r.t.RiskTxnSupport$SRE.RISK_HELPER: com.sarvatra.re.transaction.RiskEngineHelper@5ae11ea0
      c.s.r.t.RiskTxnSupport$SRE.PROFILE_KEYS: {customer-mobile=918655462548}
      c.s.r.t.RiskTxnSupport$SRE.RULES: [{"id":-5,"name":"full-kyc-per-txn-limit","status":"ACTIVE"}]
      c.s.r.t.RiskTxnSupport$SRE.PROFILE_REQUIRED: {}
      c.s.r.t.RiskTxnSupport$SRE.SUMMARY_KEYS: {}
      c.s.r.t.RiskTxnSupport$SRE.PROFILES: {}
      c.s.r.t.RiskTxnSupport$SRE.SUMMARY: {}
      c.s.r.t.RiskTxnSupport$SRE.TXN_DATA: {}
      RAW_MPIN: {{hidden-value}}
      PSO: {{hidden-value}}
      TokenSecret: {{hidden-value}}
      RTSP_MPIN: {{hidden-value}}
      PURE_PCBDC_TOKENS: true
      IS_PCBDC_TXN: true
      TOKEN_RULE_MAPPING: {b933451b184801f515b19c063f98001c83b7a6ad265056f22f766351703f1eaa={"amount":"53.00","ruleId":"ad8803b0-99c0-42ec-94eb-24995580d116"}}
      PCBDC_RULE_ID_SET: [ad8803b0-99c0-42ec-94eb-24995580d116]
      APP_TOKENS: [{"id":"b933451b184801f515b19c063f98001c83b7a6ad265056f22f766351703f1eaa","tag":"eyJpc3N1ZXJTaWduYXR1cmUiOiJtLzQ0Jy82MCcvMHxtLzQ0Jy82MCcvMjAnLzAvMHwweGI0YjU5YWQ2NThlOTg4M2QyZGNiNTQyMjBmMGEzNGQ3ZDY0NGYyNzY2YWI4ZTQwYjVkYzg4Zjc0YTc4ZWFjNDY3YmM3ODA5MGFjNmZmMTRiMDkwNDVkNGVmNmRmNGVhOGQwZGQ5OWM5YTEzODk1NTQ4ZDc3NGE4ZTU4ZjQxZjAzMDEiLCJjcmVhdGlvblRpbWVzdGFtcCI6IjIwMjUtMDYtMTJUMTU6MTE6MzMuMTAzWiIsImV4cGlyYXRpb25UaW1lc3RhbXAiOiIyMDMwLTA2LTA0VDE4OjI5OjU5Ljk5OVoiLCJjdXJyZW5jeSI6IklOUiIsIm93bmVyQWRkcmVzcyI6IjF8MHgyNjMyMEQyOTEzOTU5OGUwRTU3OWI1NDQ4OWI3RmYyZTQxYjI1MTY5IiwidG9rZW5UeXBlIjoiUENCREMiLCJydWxlSWQiOlsiYWQ4ODAzYjAtOTljMC00MmVjLTk0ZWItMjQ5OTU1ODBkMTE2Il0sImlzT2ZmbGluZVNwZW5kYWJsZSI6ImZhbHNlIn0=","value":"53.00","serialNo":"304154311791583"}]
      VALID_PIN: true
      TXN_RESPONSE: {"result":"FAILURE","errCode":"Z08","msg":"PCBDC token validation failure"}
      VALIDATION_SERVICE_REQUEST_CRED: org.npci.token.schema.Cred@72c9bb48
      VALIDATION_TARGET_POJO_TEXT: <![CDATA[
<?xml version="1.0" encoding="UTF-8" standalone="yes"?><ns2:ReqPay xmlns:ns2="http://npci.org/upi/schema/"><Head ver="2.0" ts="2025-06-16T17:25:58+05:30" orgId="159002" msgId="5zvhPd0QCc4gVgdgHbi" prodType="VALD"/><Txn custRef="" id="SBI7aJWyEZlEwsNmaDLfJmTaONrqaBJKdeU" note="PAY" refId="0" refUrl="http://pso" ts="2025-06-16T17:25:58+05:30" type="PBT" initiationMode="" purpose="93"/><Payer><Creds><Cred type="VALIDATION" subType=""><Datacode>eyJUb2tlbnMiOlt7IlRva2VuVHlwZSI6IlBCVCIsIlRhZyI6eyJydWxlSWQiOiJhZDg4MDNiMC05OWMwLTQyZWMtOTRlYi0yNDk5NTU4MGQxMTYifSwiVG9rZW5JRCI6ImI5MzM0NTFiMTg0ODAxZjUxNWIxOWMwNjNmOTgwMDFjODNiN2E2YWQyNjUwNTZmMjJmNzY2MzUxNzAzZjFlYWEifV19</Datacode></Cred><Cred type="SIGN" subType=""><Datacode></Datacode></Cred></Creds></Payer><Payees><Payee addr="1BDo8V1sieDt6oqm75K7mHtmmdopfrDib2@drsbi" code="0000"><Device><Tag name="GEOCODE" value="19.0222,73.0170"/></Device><Ac addrType="WALLET"><Detail name="ACTYPE" value="WALLET"/><Detail name="TSPID" value="159002"/><Detail name="WALLETADDRESS" value="1BDo8V1sieDt6oqm75K7mHtmmdopfrDib2"/></Ac></Payee></Payees></ns2:ReqPay>
]]>

      TARGET_POJO: org.npci.pso.schema.RespPay@4f0948d6
      XML_REQUEST: {wiped}
      VALIDATION_SERVICE_REQUEST: org.npci.pso.schema.ReqPay@5c4132d3
 VALIDATION_SERVICE_EXTENDED_URL: ReqPay
      VALIDATION_SERVICE_SIGN_DATA: eyJUb2tlbnMiOlt7IlRva2VuVHlwZSI6IlBCVCIsIlRhZyI6eyJydWxlSWQiOiJhZDg4MDNiMC05OWMwLTQyZWMtOTRlYi0yNDk5NTU4MGQxMTYifSwiVG9rZW5JRCI6ImI5MzM0NTFiMTg0ODAxZjUxNWIxOWMwNjNmOTgwMDFjODNiN2E2YWQyNjUwNTZmMjJmNzY2MzUxNzAzZjFlYWEifV19
      TARGET_ENDPOINT: {"name":"PSO-FIN","signingPublicKey":true}
      NPCI_RESPONSE: <![CDATA[
<?xml version="1.0" encoding="UTF-8" standalone="yes"?><ns2:Ack xmlns:ns2="http://npci.org/upi/schema/" api="RespPay" reqMsgId="5zvhPd0QCc4gVgdgHbi" ts="2025-06-16T17:25:59+05:30"/>
]]>

      NPCI_ACK: com.sarvatra.rtsp.dto.base.Ack@4375afeb
      RC: pcbdc.token.validation.error
      EXTRC: PCBDC token validation failure
      DURATION: 1360
    </context>
            prepare: o.j.j.PrepareContext:PrepareContext PREPARED NO_JOIN
            prepare: o.j.t.Open:open PREPARED READONLY NO_JOIN
            prepare: o.j.t.p.Switch:Switch PREPARED READONLY NO_JOIN
           selector: 'init-fin-api parse-fin-txn fetch-token-wallet check-rules parse-request-creds wallet-pin-validation handle-debit check-kcc-rule-abort-flow prepare-pay-response save-db select-pso-fin-endpoint route-to-endpoint close'
            prepare: c.s.r.t.CreateFinancialTranlog:create-tranlog PREPARED NO_JOIN
            prepare: c.s.r.t.EnsureLock:ensure-lock(only-lock) PREPARED NO_JOIN
            prepare: c.s.r.t.CheckDuplicate:check-duplicate(pso) PREPARED NO_JOIN
            prepare: c.s.r.t.t.ParseFinTxnDetails:parse-fin-txn-details PREPARED NO_JOIN
            prepare: c.s.r.t.w.FetchWallet:fetch-wallet PREPARED NO_JOIN
            prepare: c.s.r.t.u.CheckProfileRuleApplicableContext:check-cooling-period PREPARED NO_JOIN
            prepare: c.s.r.t.u.CheckPcbdcNoKycTransaction:check-pcbdc-no-kyc-txn PREPARED NO_JOIN
            prepare: c.s.r.t.s.PrepareForRuleCheck:prepare-for-check PREPARED NO_JOIN
            prepare: c.s.r.t.LoadMappedProfile:load-mapped-profile(sre-lite) PREPARED NO_JOIN
            prepare: c.s.r.t.CheckApplicableRules:check-rules(sre-lite) PREPARED NO_JOIN
            prepare: c.s.r.t.EnsureRiskProfiles:ensure-risk-profiles(sre-lite) PREPARED NO_JOIN
            prepare: c.s.r.t.ValidateRuleSummary:validate-summary(sre-lite) PREPARED NO_JOIN
            prepare: c.s.r.t.u.ParseCredBlocks:parse-req-block PREPARED NO_JOIN
            prepare: c.s.r.t.s.BaseCredentialsDecryptEngine:decrypt-cred-block PREPARED NO_JOIN
            prepare: c.s.r.t.c.DecodeCredBlocks:decode-cl-blocks PREPARED NO_JOIN
            prepare: o.j.t.p.Switch:check-wallet-cred PREPARED READONLY NO_JOIN
           selector: 'check-wallet-pin'
            prepare: c.s.r.t.u.CheckPIN:check-wallet-pin PREPARED NO_JOIN
            prepare: c.s.r.t.NormalizeFinalResponse:normalize-final-response PREPARED NO_JOIN
            prepare: o.j.t.p.Switch:process-req-pay PREPARED READONLY NO_JOIN
           selector: 'prepare-req-pay-vald select-validation-service-endpoint route-to-endpoint parse-validation-service-response check-kcc-rule'
            prepare: c.s.r.t.t.p.PrepareReqPayVald:pcbdc-validation-service PREPARED NO_JOIN
            prepare: c.s.r.t.SetTargetEndpoint:set-pso-endpoint PREPARED NO_JOIN
            prepare: c.s.r.t.SignValidationServicePayload:sign-validation-service-payload PREPARED NO_JOIN
            prepare: c.s.r.t.PrepareXml:prepare-xml PREPARED NO_JOIN
            prepare: c.s.r.t.SignPayload:sign-payload PREPARED NO_JOIN
 prepareForAbort: c.s.r.t.PrepareSecurePayload:secure-response
           selector: 'send-with-http'
    prepareForAbort: c.s.r.t.QueryHttp:query-http
    prepareForAbort: c.s.r.t.UpdateSummaryStatus:update-risk-summary-status(sre-lite)
    prepareForAbort: c.s.r.t.LogDuration:log-duration
    prepareForAbort: o.j.t.Close:close
    prepareForAbort: c.s.r.t.LogCleanup:clean-up
    prepareForAbort: c.s.r.t.ReleaseLocks:release-locks
    prepareForAbort: c.s.r.t.n.QueueSmsNotification:queue-sms-notification
    prepareForAbort: c.s.r.t.a.PurgeAsyncDataCache:purge-async-cache
    prepareForAbort: o.j.j.ProtectDebugInfo:protect-debug-info
              abort: c.s.r.t.ParseValidationServiceResponse:parse-rule-creation-response
              abort: c.s.r.t.ValidateKccTransaction:validate-kcc-transaction
              abort: c.s.r.t.ValidateKccTransaction:validate-kcc-transaction(abort flow)
              abort: c.s.r.t.NormalizeFinalResponse:normalize-final-response
              abort: c.s.r.t.t.p.PrepareRespPay:prepare-resp-pay
              abort: c.s.r.t.u.SaveDB:save-db(pso)
              abort: c.s.r.t.SetTargetEndpoint:set-pso-endpoint
              abort: c.s.r.t.PrepareXml:prepare-xml
              abort: c.s.r.t.SignPayload:sign-payload
              abort: c.s.r.t.PrepareSecurePayload:secure-response
              abort: c.s.r.t.QueryHttp:query-http
              abort: c.s.r.t.LogDuration:log-duration
              abort: o.j.t.Close:close
              abort: c.s.r.t.LogCleanup:clean-up
              abort: c.s.r.t.ReleaseLocks:release-locks
              abort: c.s.r.t.n.QueueSmsNotification:queue-sms-notification
              abort: c.s.r.t.a.PurgeAsyncDataCache:purge-async-cache
              abort: o.j.j.ProtectDebugInfo:protect-debug-info
     in-transit=0/0, head=648, tail=648, paused=0, outstanding=0, active-sessions=100/100, tps=0, peak=4, avg=0.14, elapsed=1367ms
    <profiler>
      prepare: o.j.j.PrepareContext:PrepareContext [0.1/0.1]
      prepare: o.j.t.Open:open [1.6/1.7]
      prepare: o.j.t.p.Switch:Switch [0.0/1.8]
      prepare: c.s.r.t.CreateFinancialTranlog:create-tranlog [22.1/24.0]
      prepare: c.s.r.t.EnsureLock:ensure-lock(only-lock) [18.4/42.4]
      prepare: c.s.r.t.CheckDuplicate:check-duplicate(pso) [215.5/258.0]
      prepare: c.s.r.t.t.ParseFinTxnDetails:parse-fin-txn-details [196.0/454.0]
      prepare: c.s.r.t.w.FetchWallet:fetch-wallet [9.3/463.3]
      prepare: c.s.r.t.u.CheckProfileRuleApplicableContext:check-cooling-period [2.5/465.8]
      prepare: c.s.r.t.u.CheckPcbdcNoKycTransaction:check-pcbdc-no-kyc-txn [0.1/466.0]
      prepare: c.s.r.t.s.PrepareForRuleCheck:prepare-for-check [0.1/466.1]
      prepare: c.s.r.t.LoadMappedProfile:load-mapped-profile(sre-lite) [0.0/466.2]
      prepare: c.s.r.t.CheckApplicableRules:check-rules(sre-lite) [0.1/466.3]
      prepare: c.s.r.t.EnsureRiskProfiles:ensure-risk-profiles(sre-lite) [0.0/466.4]
      prepare: c.s.r.t.ValidateRuleSummary:validate-summary(sre-lite) [0.1/466.5]
 prepare: c.s.r.t.u.ParseCredBlocks:parse-req-block [0.1/466.7]
      prepare: c.s.r.t.s.BaseCredentialsDecryptEngine:decrypt-cred-block [265.8/732.5]
      prepare: c.s.r.t.c.DecodeCredBlocks:decode-cl-blocks [0.5/733.1]
      prepare: o.j.t.p.Switch:check-wallet-cred [0.0/733.2]
      prepare: c.s.r.t.u.CheckPIN:check-wallet-pin [0.0/733.3]
      prepare: c.s.r.t.NormalizeFinalResponse:normalize-final-response [0.0/733.3]
      prepare: o.j.t.p.Switch:process-req-pay [0.0/733.3]
      prepare: c.s.r.t.t.p.PrepareReqPayVald:pcbdc-validation-service [1.0/734.4]
      prepare: c.s.r.t.SetTargetEndpoint:set-pso-endpoint [0.0/734.5]
      prepare: c.s.r.t.SignValidationServicePayload:sign-validation-service-payload [62.1/796.6]
      prepare: c.s.r.t.PrepareXml:prepare-xml [0.3/797.0]
      prepare: c.s.r.t.SignPayload:sign-payload [0.1/797.2]
      prepare: c.s.r.t.PrepareSecurePayload:secure-response [0.0/797.3]
      prepare: o.j.t.p.Switch:check-notify-transfer-token [0.0/797.3]
      prepare: c.s.r.t.QueryHttp:query-http [115.4/912.7]
      prepare: c.s.r.t.ParseValidationServiceResponse:parse-rule-creation-response [1.8/914.5]
      prepareForAbort: c.s.r.t.ParseTokenValidationResponse:parse-token-validation-response [309.3/1223.9]
      prepareForAbort: c.s.r.t.ValidateKccTransaction:validate-kcc-transaction [0.2/1224.1]
      prepareForAbort: c.s.r.t.ValidateKccTransaction:validate-kcc-transaction(abort flow) [0.2/1224.3]
      prepareForAbort: c.s.r.t.NormalizeFinalResponse:normalize-final-response [0.1/1224.5]
      prepareForAbort: c.s.r.t.t.p.PrepareRespPay:prepare-resp-pay [0.2/1224.7]
      prepareForAbort: c.s.r.t.u.SaveDB:save-db(pso) [102.5/1327.2]
      prepareForAbort: c.s.r.t.SetTargetEndpoint:set-pso-endpoint [0.1/1327.4]
      prepareForAbort: c.s.r.t.PrepareXml:prepare-xml [0.2/1327.6]
      prepareForAbort: c.s.r.t.SignPayload:sign-payload [6.2/1333.9]
      prepareForAbort: c.s.r.t.PrepareSecurePayload:secure-response [0.0/1333.9]
      prepareForAbort: c.s.r.t.QueryHttp:query-http [26.2/1360.2]
      prepareForAbort: c.s.r.t.UpdateSummaryStatus:update-risk-summary-status(sre-lite) [0.1/1360.3]
      prepareForAbort: c.s.r.t.LogDuration:log-duration [0.0/1360.3]
      prepareForAbort: o.j.t.Close:close [0.0/1360.4]
      prepareForAbort: c.s.r.t.LogCleanup:clean-up [0.0/1360.4]
      prepareForAbort: c.s.r.t.ReleaseLocks:release-locks [0.0/1360.4]
      prepareForAbort: c.s.r.t.n.QueueSmsNotification:queue-sms-notification [0.0/1360.4]
      prepareForAbort: c.s.r.t.a.PurgeAsyncDataCache:purge-async-cache [0.0/1360.5]
      prepareForAbort: o.j.j.ProtectDebugInfo:protect-debug-info [0.0/1360.5]
        abort: c.s.r.t.ParseValidationServiceResponse:parse-rule-creation-response [0.1/1360.6]
        abort: c.s.r.t.ValidateKccTransaction:validate-kcc-transaction [0.0/1360.6]
        abort: c.s.r.t.ValidateKccTransaction:validate-kcc-transaction(abort flow) [0.0/1360.7]
        abort: c.s.r.t.NormalizeFinalResponse:normalize-final-response [0.0/1360.7]
        abort: c.s.r.t.t.p.PrepareRespPay:prepare-resp-pay [0.0/1360.7]
        abort: c.s.r.t.u.SaveDB:save-db(pso) [0.0/1360.7]
        abort: c.s.r.t.SetTargetEndpoint:set-pso-endpoint [0.0/1360.7]
        abort: c.s.r.t.PrepareXml:prepare-xml [0.0/1360.7]
        abort: c.s.r.t.SignPayload:sign-payload [0.0/1360.7]
        abort: c.s.r.t.PrepareSecurePayload:secure-response [0.0/1360.8]
abort: c.s.r.t.PrepareSecurePayload:secure-response [0.0/1360.8]
        abort: c.s.r.t.QueryHttp:query-http [0.0/1360.8]
        abort: c.s.r.t.LogDuration:log-duration [0.0/1360.8]
        abort: o.j.t.Close:close [3.5/1364.4]
        abort: c.s.r.t.LogCleanup:clean-up [0.0/1364.5]
        abort: c.s.r.t.ReleaseLocks:release-locks [0.2/1364.7]
        abort: c.s.r.t.n.QueueSmsNotification:queue-sms-notification [0.0/1364.8]
        abort: c.s.r.t.a.PurgeAsyncDataCache:purge-async-cache [0.0/1364.8]
        abort: o.j.j.ProtectDebugInfo:protect-debug-info [0.6/1365.4]
      end [3.7/1369.2]
    </profiler>
  </abort>
</log>

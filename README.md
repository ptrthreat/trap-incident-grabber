# trap-incident-grabber
Retrieve specific TRAP incident details


## EXAMPLE Run

### > ./trapinc-mac-arm64 -incident=100

```json
{
   "assignee": "Unassigned",
   "close_detail": "Message being closed due to age",
   "close_summary": "Closing Incident",
   "closed_at": "2022-05-06T06:14:48Z",
   "comments": [
      {
         "commented_on": "2022-05-03T23:53:02Z",
         "detail": "",
         "summary": "all open 744",
         "user": "admin"
      },
      {
         "commented_on": "2022-05-04T09:03:49Z",
         "detail": "",
         "summary": "open",
         "user": "admin"
      },
      {
         "commented_on": "2022-05-04T09:07:11Z",
         "detail": "",
         "summary": "open",
         "user": "admin"
      },
      {
         "commented_on": "2022-05-04T15:01:11Z",
         "detail": "",
         "summary": "open",
         "user": "admin"
      },
      {
         "commented_on": "2022-05-04T17:55:36Z",
         "detail": "",
         "summary": "open 801",
         "user": "admin"
      },
      {
         "commented_on": "2022-05-04T20:49:37Z",
         "detail": "",
         "summary": "open 801 2",
         "user": "admin"
      },
      {
         "commented_on": "2022-05-05T01:38:25Z",
         "detail": "",
         "summary": "open",
         "user": "admin"
      },
      {
         "commented_on": "2022-05-05T02:39:46Z",
         "detail": "",
         "summary": "open",
         "user": "admin"
      },
      {
         "commented_on": "2022-05-05T03:04:40Z",
         "detail": "",
         "summary": "open",
         "user": "admin"
      },
      {
         "commented_on": "2022-05-05T04:27:10Z",
         "detail": "",
         "summary": "open",
         "user": "admin"
      }
   ],
   "created_at": "2022-02-24T05:51:58Z",
   "description": "",
   "event_count": 1,
   "event_ids": null,
   "event_sources": [
      "Abuse o365"
   ],
   "events": [
      {
         "alertType": "Reported Abuse",
         "attackDirection": "inbound",
         "emails": [
            {
               "abuseCopy": true,
               "abuseReporterAddress": "abuse@pfpt100.com",
               "body": "\u003c!DOCTYPE html\u003e\u003chtml xmlns=\"http://www.w3.org/1999/xhtml\"\u003e\u003chead\u003e\u003c!-- BaNnErBlUrFlE-HeAdEr-start --\u003e\u003cmeta http-equiv=\"Content-Type\" content=\"text/html; charset=utf-8\"\u003e\u003cmeta name=\"viewport\" content=\"width=device-width, initial-scale=1.0\"\u003e\u003cstyle\u003e\n      .pfptBannerTableMSO { padding: 0px 12px 5px 12px; width: 100%;border-radius:4px;border-top:4px solid #90a4ae;background-color:#D0D8DC; }\n      .pfptTitleMSO { color:#000000 !important;font-family: 'Arial', sans-serif !important;font-weight:bold !important;font-size:14px !important; }\n      .pfptSubtitleMSO { font-size:12px !important; font-family: 'Arial', sans-serif !important; }\n      .pfptButtonMSO { mso-padding-alt: 7.5px; padding: 7.5px; text-decoration: none; font-family: 'Arial', sans-serif !important; font-size: 14px; line-height: 40px; border-radius:2px; }\n      .pfptPrimaryButtonMSO {\n\tborder: 1.5px solid #666666; color: #000000;\n      }\n     .pfptBanner {\n\tmargin: 15px 14px 30px 14px;\n\tpadding: 8px 16px 8px 16px;\n\tborder-radius: 4px;\n\tmin-width: 200px;\n\tbackground-color: #D0D8DC;\n\tborder-top: 4px solid #90a4ae;\n      }\n      .pfptBannerTitle {\n\tcolor: #000000;\n\tfont-family: 'Arial', sans-serif;\n\tfont-size: 14px;\n\tfont-weight: bold;\n\tline-height: 18px;\n\tdisplay: block;\n      }\n      .pfptBannerSubtitle {\n\tcolor: #000000;\n\tfont-weight: normal;\n\tfont-family: 'Arial', sans-serif;\n\tfont-size: 12px;\n\tline-height: 18px;\n\tmargin-top: 2px;\n\tdisplay: block;\n      }\n      .pfptButton {\n\tdisplay: inline-block;\n\tfont-family: 'Arial', sans-serif;\n\tfont-size: 14px;\n\tfont-weight: normal;\n\tborder-radius: 2px;\n\tpadding: 7.5px 16px;\n\tmargin: 3px 0 3px 16px;\n\twhite-space: nowrap;\n\twidth: fit-content;\n      }\n      .pfptPrimaryButton {\n\tborder: 1px solid #666666;\n      }\n      .pfptPrimaryButton:hover, .pfptPrimaryButton:focus {\n\tbackground-color: #b4c1c7;\n      }\n      .pfptPrimaryButton:active {\n\tbackground-color: #90a4ae;\n      }\n      .pfptMessageContainer {\n\tdisplay: inline-block;\n\tmargin: 0px 0px 1px 0px;\n\tmax-width: 600px;\n      }\n      .pfptButtonGroup {\n\tfloat: right;\n\tmargin: 0px 0px 0px 16px;\n\ttext-align: right;\n\twidth: fit-content;\n      }\n      .pfptPreheader { display:none !important; visibility:hidden; mso-hide:all; font-size:1px; line-height:1px; max-height:0px; max-width:0px; opacity:0; overflow:hidden; }\u003c/style\u003e\u003c!-- BaNnErBlUrFlE-HeAdEr-end --\u003e\u003cmeta name=\"viewport\" content=\"width=device-width, initial-scale=1\"\u003e\u003cmeta http-equiv=\"X-UA-Compatible\" content=\"IE=edge\"\u003e\u003cstyle\u003e\n            body, table, td { font-family: Segoe UI, Helvetica, Arial, sans-serif !important; }\n            a { color: #006CBE; text-decoration: none; }\u003c/style\u003e\u003c/head\u003e\u003cbody\u003e\u003c!-- BaNnErBlUrFlE-BoDy-start --\u003e\u003c!-- Preheader Text : BEGIN --\u003e\u003cspan class=\"pfptPreheader\" style=\"display:none !important;visibility:hidden;mso-hide:all;font-size:1px;color:#ffffff;line-height:1px;max-height:0px;max-width:0px;opacity:0;overflow:hidden;\"\u003e‍ ‍ ‍ ‍ ‍ ‍ ‍ ‍ ‍ ‍ ‍ ‍ ‍ ‍ ‍ ‍ ‍ ‍ ‍ ‍ ‍ ‍ ‍ ‍ ‍ ‍ ‍ ‍ ‍ ‍ ‍ ‍ ‍ ‍ ‍ ‍ ‍ ‍ ‍ ‍ ‍ ‍ ‍ ‍ ‍ ‍ ‍ ‍ ‍ ‍ ‍ ‍ ‍ ‍ ‍ ‍ ‍ ‍ ‍ ‍ ‍ ‍ ‍ ‍ ‍ ‍ ‍ ‍ ‍ ‍ ‍ ‍ ‍ ‍ ‍ ‍ ‍ ‍ ‍ ‍ ‍ ‍ ‍ ‍ ‍ ‍ ‍ ‍ ‍ ‍ ‍ ‍ ‍ ‍ ‍ ‍ ‍ ‍ ‍ ‍ ‍ ‍ ‍ ‍ ‍ ‍ ‍ ‍ ‍ ‍ ‍ ‍ ‍ ‍ ‍ ‍ ‍ ‍ ‍ ‍ ‍ ‍ ‍ ‍ ‍ ‍ ‍ ‍ ‍ ‍ ‍ ‍ ‍ ‍ ‍ ‍ ‍ ‍ ‍ ‍ ‍ ‍ ‍ ‍ ‍ ‍ ‍ ‍ ‍ ‍ ‍ ‍ ‍ ‍ ‍ ‍ ‍ ‍ ‍ ‍ ‍ ‍ ‍ ‍ ‍ ‍ ‍ ‍ ‍ ‍ ‍ ‍ ‍ ‍ ‍ ‍ ‍ ‍ ‍ ‍ ‍ ‍ ‍ ‍ ‍ ‍ ‍ ‍ ‍ ‍ ‍ ‍ ‍ ‍ ‍ ‍ ‍ ‍ ‍ ‍ ‍ ‍ ‍ ‍ ‍ ‍ ‍ ‍ ‍ ‍ ‍ ‍ ‍ ‍ ‍ ‍ ‍ ‍ ‍ ‍ ‍ ‍ ‍ ‍ ‍ ‍ ‍ ‍ ‍ ‍ ‍ ‍ ‍ ‍ ‍ ‍ ‍ ‍ ‍ \u003c/span\u003e\u003c!-- Preheader Text : END --\u003e\u003c!-- Email Banner : BEGIN --\u003e\u003cspan style=\"display:none !important;visibility:hidden;mso-hide:all;font-size:1px;color:#ffffff;line-height:1px;max-height:0px;max-width:0px;opacity:0;overflow:hidden;\"\u003eZjQcmQRYFpfptBannerStart\u003c/span\u003e\u003c!--[if ((ie)|(mso))]\u003e\u003ctable border=\"0\" cellspacing=\"0\" cellpadding=\"0\" width=\"100%\" style=\"padding: 3px 0px 16px 0px; direction: ltr\" \u003e\u003ctr\u003e\u003ctd\u003e\u003ctable class=\"pfptBannerTableMSO\" border=\"0\" cellspacing=\"0\" cellpadding=\"0\" style=\"padding: 0px 10px 5px 6px; width: 100%;border-radius:4px;border-top:4px solid #90a4ae;background-color:#D0D8DC;\"\u003e\u003ctr\u003e\u003ctd valign=\"top\"\u003e\u003ctable align=\"left\" border=\"0\" cellspacing=\"0\" cellpadding=\"0\" style=\"padding: 4px 8px 4px 8px\"\u003e\u003ctr\u003e\u003ctd\u003e\u003cspan class=\"pfptTitleMSO\" style=\"color:#000000 !important;font-family: 'Arial', sans-serif;font-weight:bold !important;font-size:14px !important; direction: ltr\"\u003e\n\t  This Message Is From an External Sender\u003c/span\u003e\u003c/td\u003e\u003c/tr\u003e\u003ctr\u003e\u003ctd\u003e\u003cspan class=\"pfptSubtitleMSO\" style=\"color:#000000 !important;font-weight:normal !important;font-family: 'Arial', sans-serif; font-size:12px !important; direction: ltr\"\u003e\n          This message came from outside your organization.\u003c/span\u003e\u003c/td\u003e\u003c/tr\u003e\u003c/table\u003e\u003c/td\u003e\u003c/tr\u003e\u003c/table\u003e\u003c/td\u003e\u003c/tr\u003e\u003c/table\u003e\u003c![endif]--\u003e\u003c![if !((ie)|(mso))]\u003e\u003cdiv dir=\"ltr\" class=\"pfptBanner\" style=\"margin:16px 0px 16px 0px; padding:8px 16px 8px 16px; border-radius: 4px; min-width: 200px;background-color: #D0D8DC; border-top: 4px solid #90a4ae;\"\u003e\u003cdiv class=\"pfptMessageContainer\" style=\"display: inline-block; margin: 0px 0px 1px 0px; max-width: 600px;\"\u003e\u003cdiv class=\"pfptBannerTitle\" style=\"color:#000000 !important;font-family: 'Arial', sans-serif !important;font-weight:bold !important;font-size:14px !important;line-height:18px;display:block;\"\u003eThis Message Is From an External Sender \u003c/div\u003e\u003cdiv class=\"pfptBannerSubtitle\" style=\"color:#000000 !important;font-weight:normal !important;font-family: 'Arial', sans-serif !important;font-size:12px !important;line-height:18px;margin-top:2px;display:block\"\u003eThis message came from outside your organization. \u003c/div\u003e\u003c/div\u003e\u003c/div\u003e\u003c![endif]\u003e\u003cdiv style=\"display:none !important;visibility:hidden;mso-hide:all;font-size:1px;color:#ffffff;line-height:1px;max-height:0px;max-width:0px;opacity:0;overflow:hidden;\"\u003eZjQcmQRYFpfptBannerEnd\u003c/div\u003e\u003c!-- Email Banner : END --\u003e\u003c!-- BaNnErBlUrFlE-BoDy-end --\u003e\u003c!-- Outer wrapper --\u003e\u003cdiv style=\"background: white; min-height: 100vh; color: #323130; font-size: 14px;\"\u003e\u003ctable border=\"0\" cellpadding=\"0\" cellspacing=\"0\" width=\"100%\" height=\"100%\"\u003e\u003ctbody\u003e\u003ctr\u003e\u003ctd\u003e\u003c/td\u003e\u003ctd width=\"640\"\u003e\u003c!-- Inner wrapper --\u003e\u003ctable border=\"0\" cellpadding=\"0\" cellspacing=\"0\" style=\"min-width: 100%; background: white;\"\u003e\u003c!-- Logo --\u003e\u003ctbody\u003e\u003ctr\u003e\u003ctd style=\"padding: 24px 24px 45px;\"\u003e\u003cimg src=\"https://eus-contentstorage.osi.office.net/images/retailer.images/centralizeddeployment/logos/112fec798b78aa02.png\" width=\"100\" height=\"21\" alt=\"Microsoft\"\u003e\u003c/td\u003e\u003c/tr\u003e\u003c!-- Title --\u003e\u003ctr\u003e\u003ctd style=\"font-size: 28px; padding: 0 24px; font-weight: bold; color: #000000\"\u003eLinkedIn Integration coming to Teams\u003c/td\u003e\u003c/tr\u003e\u003c!-- Sub-header / Company name --\u003e\u003ctr\u003e\u003ctd style=\"color: #323130; padding: 20px 24px 40px 24px;\"\u003e\u003cspan style=\"font-weight: 600\"\u003eMC335277 · PFPT100\u003c/span\u003e\u003c/td\u003e\u003c/tr\u003e\u003c!-- Main content --\u003e\u003ctr\u003e\u003ctd style=\"padding: 0 24px 44px;\"\u003e\u003cdiv\u003e\u003cp style=\"margin-top: 0\"\u003eFor those tenants that have LinkedIn integration available to their members, we are expanding its availability to Teams as a panel in one on one conversations. This is the first part of a series of updates which will also bring LinkedIn to the contact card in the coming months.\u0026nbsp; Initially this is limited to contacts within the tenant, but as the contact card updates are released, then this will be available for all contacts within and outside the tenant.\u003cbr\u003e\u003c/p\u003e\u003cp\u003eThis message is associated with Microsoft 365 Roadmap ID \u003ca href=\"https://urldefense.com/v3/__https://www.microsoft.com/microsoft-365/roadmap?filters=\u0026amp;searchterms=89132__;!!DfHvcUuWuuyr!59KccvthRTpMtDxYKoVlj7vkYuvNxlupWAfAsARsKkR39KAwkJ6N8zIeBTcv1yFl$\" target=\"_blank\"\u003e89132\u003c/a\u003e\u003cbr\u003e\u003c/p\u003e\u003cp\u003e\u003cb style=\"font-weight: 600\"\u003eWhen this will happen:\u003c/b\u003e\u003cbr\u003e\u003c/p\u003e\u003cp\u003eWe will begin rolling this out in mid-March and expect to complete by early April.\u003c/p\u003e\u003cp\u003e\u003cb style=\"font-weight: 600\"\u003eHow this will affect your organization:\u003c/b\u003e\u003cbr\u003e\u003c/p\u003e\u003cp\u003eOnce available, the new LinkedIn tab will appear at the top of the 1:1 conversation in Teams alongside the existing tabs for Chat, Files, Organization and Activity, and will work just like the contact card in Outlook does today.\u003c/p\u003e\u003cp\u003e\u003cimg src=\"https://img-prod-cms-rt-microsoft-com.akamaized.net/cms/api/am/imageFileData/RWWrZs?ver=3d7d\" alt=\"LinkedIn Menu Option\" width=\"400\" height=\"\"\u003e\u003c/p\u003e\u003cp\u003eYou continue to have the same controls as before over the integration availability.\u0026nbsp; This is just making the experience available in more places for your members.\u003c/p\u003e\u003cp\u003e\u003cb style=\"font-weight: 600\"\u003eWhat you need to do to prepare:\u003c/b\u003e\u003c/p\u003e\u003cp\u003e\u003c/p\u003e\u003cp\u003eReview your current configuration to ensure the appropriate experience for your organization.\u003c/p\u003e\u003cp\u003eTo learn about existing controls, review:\u0026nbsp;\u003ca href=\"https://urldefense.com/v3/__https://docs.microsoft.com/azure/active-directory/users-groups-roles/linkedin-integration__;!!DfHvcUuWuuyr!59KccvthRTpMtDxYKoVlj7vkYuvNxlupWAfAsARsKkR39KAwkJ6N8zIeBU7Yqr-6$\" target=\"_blank\"\u003eIntegrate LinkedIn account connections in Azure Active Directory\u003c/a\u003e\u003c/p\u003e\u003ca href=\"https://urldefense.com/v3/__https://docs.microsoft.com/azure/active-directory/enterprise-users/linkedin-integration__;!!DfHvcUuWuuyr!59KccvthRTpMtDxYKoVlj7vkYuvNxlupWAfAsARsKkR39KAwkJ6N8zIeBdadrnub$\" title=\"Additional Information\"\u003eAdditional Information\u003c/a\u003e\u003c/div\u003e\u003cdiv style=\"padding-top: 3px\"\u003e\u003ca href=\"https://urldefense.com/v3/__https://admin.microsoft.com/AdminPortal/home*/MessageCenter/:/messages/MC335277?MCLinkSource=MajorUpdate__;Iw!!DfHvcUuWuuyr!59KccvthRTpMtDxYKoVlj7vkYuvNxlupWAfAsARsKkR39KAwkJ6N8zIeBZK6WNPk$\" title=\"view message\" target=\"_blank\"\u003eView this message in the Microsoft 365 admin center\u003c/a\u003e\u003c/div\u003e\u003c/td\u003e\u003c/tr\u003e\u003c!-- Footer --\u003e\u003ctr\u003e\u003ctd\u003e\u003ctable border=\"0\" cellpadding=\"0\" cellspacing=\"0\" width=\"100%\" style=\"min-width: 100%; background-color: #F3F2F1;\"\u003e\u003c!-- Disclaimer --\u003e\u003ctbody\u003e\u003ctr\u003e\u003ctd style=\"padding: 44px 24px 3px; font-size: 10px; color: #484644\"\u003eYou're subscribed to this email using abuse@pfpt100.com. If you're an IT admin, you're subscribed by default, but you can \u003ca href=\"https://urldefense.com/v3/__https://admin.microsoft.com/adminportal/home*/MessageCenter/:/mcpreferences__;Iw!!DfHvcUuWuuyr!59KccvthRTpMtDxYKoVlj7vkYuvNxlupWAfAsARsKkR39KAwkJ6N8zIeBRxCf0F6$\" target=\"_blank\"\u003eunsubscribe at any time\u003c/a\u003e. If you're not an IT admin, ask your admin to remove your email address from Microsoft 365 message center preferences.\u003cbr\u003e\u003cbr\u003e\u003ca href=\"https://urldefense.com/v3/__https://docs.microsoft.com/en-us/microsoft-365/admin/manage/language-translation-for-message-center-posts?view=o365-worldwide__;!!DfHvcUuWuuyr!59KccvthRTpMtDxYKoVlj7vkYuvNxlupWAfAsARsKkR39KAwkJ6N8zIeBcMEwkML$\" target=\"_blank\"\u003eHow to view translated messages\u003c/a\u003e\u003cbr\u003e\u003c/td\u003e\u003c/tr\u003e\u003ctr\u003e\u003ctd style=\"padding: 25px 24px 24px; font-size: 12px\"\u003e\u003ca href=\"https://urldefense.com/v3/__https://go.microsoft.com/fwlink/?LinkId=521839__;!!DfHvcUuWuuyr!59KccvthRTpMtDxYKoVlj7vkYuvNxlupWAfAsARsKkR39KAwkJ6N8zIeBQQbTKa-$\" target=\"_blank\" style=\"color:#696969; text-decoration: underline; text-decoration-color:#696969;\"\u003ePrivacy statement\u003c/a\u003e\u003cdiv style=\"color:#696969; margin-top: 10px; margin-bottom: 13px;\"\u003eMicrosoft Corporation, One Microsoft Way, Redmond WA 98052 USA\u003c/div\u003e\u003cimg src=\"https://eus-contentstorage.osi.office.net/images/retailer.images/centralizeddeployment/logos/112fec798b78aa02.png\" width=\"94\" height=\"20\" alt=\"Microsoft\"\u003e\u003c/td\u003e\u003c/tr\u003e\u003c/tbody\u003e\u003c/table\u003e\u003c/td\u003e\u003c/tr\u003e\u003c/tbody\u003e\u003c/table\u003e\u003c/td\u003e\u003ctd\u003e\u003c/td\u003e\u003c/tr\u003e\u003c/tbody\u003e\u003c/table\u003e\u003c/div\u003e\u003cimg src=\"https://mucp.api.account.microsoft.com/m/v2/v?d=AIAADI7YL2B6SL73WAMTS4CDGZ7UVQ7R2A6SKP6364LWPPIAWBPBRH2QCJXT6KTC4AAWU26UZOXKTC3VBVHZF4OFXKB4TNO3WFIAN44NLTBD3PFKN36UC5KFMD6C2DN2XJQLCWH4N2DUM2R4X42JWRRE2R2PWSQ\u0026amp;i=AIAACTHRJJBNYIMYGIMEHWP3B3PWP7AFJEQ2QHM2FAH5RBIK2QJAYECEKFRJOWQQZTMWMH7VDMCWYSRZVSS3Q4FZX4CAI6DLLG5ZCFRG56GUVZVF3AH2Z3XMF7UD4C3H62IWSSHX4KNVLWDJ5BBSL4VZQMPI24BCEC47EZV4KBRWGQ5GUY5NW47TQ6BMCFB7QZ3Q56SV2JJ5EDN4G7GSW5NTBLDWWV5RKIIRBVZQNSSUTILLOHCR7MIDZRBM6SVUPHFL4LNSTB57P55THBGYMDBBGTZN6GA\" width=\"1\" height=\"1\" tabindex=\"-1\" aria-hidden=\"true\" alt=\"\"\u003e\u003c!-- cV: WnAB9MEIgUagZxCK.4.1.1.4 --\u003e\u003c/body\u003e\u003c/html\u003e",
               "bodyType": "html",
               "headers": {
                  "Authentication-Results": "spf=fail (sender IP is 205.220.168.64) smtp.mailfrom=microsoft.com; dkim=fail (body hash did not verify) header.d=microsoft.com;dmarc=fail action=oreject header.from=microsoft.com;compauth=none reason=451",
                  "Authentication-Results-Original": "ppops.net;\tspf=pass smtp.mailfrom=o365mc@microsoft.com;\tdkim=pass header.d=microsoft.com header.s=s1024",
                  "Content-Transfer-Encoding": "quoted-printable",
                  "Content-Type": "text/html",
                  "DKIM-Signature": "v=1; a=rsa-sha256; c=relaxed/relaxed; d=microsoft.com; s=s1024; t=1645681862; h=From; bh=Nhbt7oE7lCdk+GeafjQvVqz1UUHRv+A4z6/QHcm x/yg=; b=Unu/oEpugNrYw1wAX8441KziXlJb/25i5Xf9W8icrSUdbb83RQD4iM4CpUNgZcBY PDdqKiVV0eufQjlWIi1rKE9Kd8fNoaslaNQubu0t9sWCYWQ2Z6Z0Yg9CoHmhbG0FyDKeAh3Ao dGCpQydW7AtVidGdpW4x9VFMx0R6O32z6E=;",
                  "Date": "Wed, 23 Feb 2022 21:51:02 -0800",
                  "MIME-Version": "1.0",
                  "Message-ID": "\u003ce47eea564f8140198987e9c726ba14e7-JFBVALKQOJXWILKNK4YVA7CPGM3DKTLFONZWCZ3FINSW45DFOJ6E2ZLTONQWOZKDMVXHIZLSL5GUGMZTGUZDON34KNWXI4A=@microsoft.com\u003e",
                  "Received": "from smtpi.msn.com (eus-irissmtp10.msn.com [52.234.172.105])\tby mx0a-006af001.pphosted.com (PPS) with ESMTPS id 3ed6cqrbf8-1\t(version=TLSv1.2 cipher=ECDHE-RSA-AES256-SHA384 bits=256 verify=NOT)\tfor \u003cabuse@pfpt100.com\u003e; Thu, 24 Feb 2022 05:51:04 +0000",
                  "Received-SPF": "Fail (protection.outlook.com: domain of microsoft.com does not designate 205.220.168.64 as permitted sender) receiver=protection.outlook.com; client-ip=205.220.168.64; helo=mx0a-006af001.pphosted.com;",
                  "Return-Path": "o365mc@microsoft.com",
                  "Subject": "Major update from Message center",
                  "X-DKIM-Signer": "DkimX (v3.20.320)",
                  "X-EOPAttributedMessage": "0",
                  "X-EOPTenantAttributedMessage": "2bac89e1-0311-4f18-bbb5-a229530a794a:0",
                  "X-Forefront-Antispam-Report": "CIP:205.220.168.64;CTRY:US;LANG:en;SCL:1;SRV:;IPV:NLI;SFV:NSPM;H:mx0a-006af001.pphosted.com;PTR:mx0a-006af001.pphosted.com;CAT:NONE;SFS:(13230001)(47530400004)(76236003)(7636003)(7596003)(336012)(8676002)(2616005)(956004)(26005)(166002)(356005)(10290500003)(5660300002)(19627235002)(36756003)(15650500001)(52230400001)(19627405001)(83380400001)(86362001)(6916009)(1096003)(18121605002)(15585785002);DIR:INB;",
                  "X-MS-Exchange-CrossTenant-AuthAs": "Anonymous",
                  "X-MS-Exchange-CrossTenant-AuthSource": "MW2NAM12FT042.eop-nam12.prod.protection.outlook.com",
                  "X-MS-Exchange-CrossTenant-FromEntityHeader": "Internet",
                  "X-MS-Exchange-CrossTenant-Id": "2bac89e1-0311-4f18-bbb5-a229530a794a",
                  "X-MS-Exchange-CrossTenant-Network-Message-Id": "fbd1cbcb-a1f8-455e-a0a2-08d9f759a60a",
                  "X-MS-Exchange-CrossTenant-OriginalArrivalTime": "24 Feb 2022 05:51:05.7937 (UTC)",
                  "X-MS-Exchange-Organization-AuthAs": "Anonymous",
                  "X-MS-Exchange-Organization-AuthSource": "MW2NAM12FT042.eop-nam12.prod.protection.outlook.com",
                  "X-MS-Exchange-Organization-ExpirationInterval": "1:00:00:00.0000000",
                  "X-MS-Exchange-Organization-ExpirationIntervalReason": "OriginalSubmit",
                  "X-MS-Exchange-Organization-ExpirationStartTime": "24 Feb 2022 05:51:05.9500 (UTC)",
                  "X-MS-Exchange-Organization-ExpirationStartTimeReason": "OriginalSubmit",
                  "X-MS-Exchange-Organization-MessageDirectionality": "Incoming",
                  "X-MS-Exchange-Organization-Network-Message-Id": "fbd1cbcb-a1f8-455e-a0a2-08d9f759a60a",
                  "X-MS-Exchange-Organization-SCL": "1",
                  "X-MS-Exchange-Processed-By-BccFoldering": "15.20.5017.024",
                  "X-MS-Exchange-Transport-CrossTenantHeadersStamped": "PH0PR14MB4328",
                  "X-MS-Exchange-Transport-EndToEndLatency": "00:00:02.4511501",
                  "X-MS-Iris-MetaData": "{\"Type\":null,\"Fields\":{\"InstanceID\":\"e47eea56-4f81-4019-8987-e9c726ba14e7\",\"ActivityID\":\"aa930d28-10ac-40da-b06d-52a4b3208dfd\"}}",
                  "X-MS-Office365-Filtering-Correlation-Id": "fbd1cbcb-a1f8-455e-a0a2-08d9f759a60a",
                  "X-MS-PublicTrafficType": "Email",
                  "X-MS-TrafficTypeDiagnostic": "PH0PR14MB4328:EE_",
                  "X-Microsoft-Antispam": "BCL:0;",
                  "X-Microsoft-Antispam-Mailbox-Delivery": "ucf:0;jmr:0;auth:0;dest:I;ENG:(910001)(944506458)(944626604)(920097)(930097);",
                  "X-Microsoft-Antispam-Message-Info": "0x0hRs3JpZozx6KhfwfiH6k/erAsVl2qJEArW7zq/uK+OCIPwxFDdlBTqkMr4bLAn4V9ajIXdE/Q9/hatWWl/TH4X/Wjb99WHUOtoHUi8MAmtCJvznd7xbF9PK7yS9+4csOboX5wDv/R7H+yuE/c6qRKNsiOIVD0c+V1o4cqK4sYYLrzFmODGpHlD2iZj063GVKpOSle8HRRIWu7xMWBez9/yrAJrcLlcUhDF/YA1aPZYUSQzuzlp04Dq9rGrTyi/gUnwIQu/nJOk6Et+Wj4MPPdKTy0drUh7m+2cBGHSQ5vtRo6abPDeKPPLtXiWlQ6wYAcY2VZE4czJrUFLTzJs5MV5G31Z0UbMwavs++K4y70+r9Rcskoi9yKl8TUIEuP94kgdGTR5uJg26CGkGxHRLnWD8uJi0PC8b2SStCbMYfc0IMHgK0tJTo7nZ/82En7SeKVxwCanZPAeVUpIntMyQ2HkUGqR9bFWlCuV9wTdjOQ88zNX4HqhQCbsP9USMeNiL/bIpdI7XDwBb84lPQuG8nTtv1up05ZBKIu5jDf9JsPIdy1HEFC5EiV1kvxui7SbjPGeMoRbm60Wpb/B5pJg4qHiC1SAL2cpaz1v7lx5aGgaleSm656euXxn+iv1VquBqhplSMe6+5opTG2X+g+/2076u2wymmtQ7vNSect9iuI3wP9dgVLyWIUiQwEN9sIotKXth168NKwQxDqfALnbNllDlxly+B+GWx+Wt6poiqxsoymzDqd9kWNHQ89jE0JZ6cZ002OsSCyJVOhxRvE7IxmGtWFZerlnvokPdGdmrSdyu/DTYSbw1KPqoMuWLqp3nqAiDG9eR3a9QkpLXb3ZpQQqx3oqhcZQ5lXLvMKWzpE7R1cO9r7GTg3/x5N969Glf8/5BL7fRDoVHx71MOCznMj99wdA7nwnmpntm0Vg5PgRzfFX05klzPNzaCXAFjVaRpiGxgde0z/oSvbUKuzgBRLGGn2G77bBoumdjZoDWimYphDMm5c6zXy/6N4Wd93JBwDuhlndAHKMrakUzd/HD4MaN11Z4J6dUFq12Xw4p9Tj67jx/+Cybl82oa3TUpA65oMcH2FYC9cwxJb2HrYEp/Aa+zU3HXDsFDJO6fomlii4xhOpaRfrk8wJZ8VpObxQUMcTXxUTUVmreLMFqqW+2VT2C2Gq4Eg4D15IgdqKb6h5wTkcvEJve7va/Hv0XEDElIky/DRVLAtwqrNnBqMJl+/HbDHUHXF7KxydRxdxN5LsI1C67eZjCvrEwRbEQHTVf5BXtAPOXxeiUuWDx/+7EVfwA3EFJ2+NoLtdESfbVQ7Z6gNOak5MIWJLetdj+GM4fGe+PbioCjIkCDVLV4pc6kXPo8ydsmlKEtdvdPcrqN/RVp7LJ90f5DmEUYoN15lulaaOnJU+ygrLILtZ42OqxBEblbMDbEWsSrfK1suaKaJbZSYNcV3aSFfMQBQtISEhGDmtvo46mct2WJ6dRF44dPL3lICzZc48hdLEqS259WmUiAAl7l5NCBy/RPlQnb1wCbYczWF85U23/dADAylmGcMKDnAtRg3P69ioj7fr7shaKlRNfWdBw2FkR+GbnYvcKvq+rlF7U34mvpaj5AnTji6BnB1EdhwN1HqkfY1kqsANMyX0BgK/DT24az90Un6wzM1+B/EC120zHhLTT4JF1KOtLtRUa0LL0CHA4/x5XAIrP+R4saaYNSO7HHpC+W13aYloY11/KoswhdUsz4gC8Vb4d57Svo4nFRfqk5PqW31McKghUDFIyybK0TgxeNu8zABwwBYzLVy172kp1WJ563dXopMluKMUeBqLxhHIQskijhG6LZ2usXPrJHZLtKqHqGWwHvRhIj77HrxdBG9LnfHDXsMXvJ+1y+VAe+CBEdoNdmcA1UCUBs9tb6702hX",
                  "X-Proofpoint-Banner-Trigger": "inbound",
                  "X-Proofpoint-GUID": "ZB-_fnEzClOzeq2x42K25pTaOiBejTor",
                  "X-Proofpoint-ORIG-GUID": "ZB-_fnEzClOzeq2x42K25pTaOiBejTor",
                  "X-Proofpoint-Spam-Details": "rule=notspam policy=default score=0 bulkscore=0 mlxlogscore=613 suspectscore=0 phishscore=0 mlxscore=0 adultscore=0 malwarescore=0 spamscore=0 classifier=spam adjust=0 reason=mlx scancount=1 engine=8.12.0-2201110000 definitions=main-2202240033",
                  "X-Proofpoint-Virus-Version": "vendor=baseguard engine=ICAP:2.0.205,Aquarius:18.0.816,Hydra:6.0.425,FMLib:17.11.64.514 definitions=2022-02-23_09,2022-02-23_01,2022-02-23_01"
               },
               "messageId": "\u003ce47eea564f8140198987e9c726ba14e7-JFBVALKQOJXWILKNK4YVA7CPGM3DKTLFONZWCZ3FINSW45DFOJ6E2ZLTONQWOZKDMVXHIZLSL5GUGMZTGUZDON34KNWXI4A=@microsoft.com\u003e",
               "recipient": {
                  "email": "abuse@pfpt100.com",
                  "vap": false
               },
               "sender": {
                  "email": "o365mc@microsoft.com",
                  "vap": false
               },
               "subject": "Major update from Message center",
               "urls": [
                  "https://urldefense.com/v3/__https://admin.microsoft.com/adminportal/home*/MessageCenter/:/mcpreferences__;Iw!!DfHvcUuWuuyr!59KccvthRTpMtDxYKoVlj7vkYuvNxlupWAfAsARsKkR39KAwkJ6N8zIeBRxCf0F6$",
                  "https://eus-contentstorage.osi.office.net/images/retailer.images/centralizeddeployment/logos/112fec798b78aa02.png",
                  "https://mucp.api.account.microsoft.com/m/v2/v?d=AIAADI7YL2B6SL73WAMTS4CDGZ7UVQ7R2A6SKP6364LWPPIAWBPBRH2QCJXT6KTC4AAWU26UZOXKTC3VBVHZF4OFXKB4TNO3WFIAN44NLTBD3PFKN36UC5KFMD6C2DN2XJQLCWH4N2DUM2R4X42JWRRE2R2PWSQ\u0026i=AIAACTHRJJBNYIMYGIMEHWP3B3PWP7AFJEQ2QHM2FAH5RBIK2QJAYECEKFRJOWQQZTMWMH7VDMCWYSRZVSS3Q4FZX4CAI6DLLG5ZCFRG56GUVZVF3AH2Z3XMF7UD4C3H62IWSSHX4KNVLWDJ5BBSL4VZQMPI24BCEC47EZV4KBRWGQ5GUY5NW47TQ6BMCFB7QZ3Q56SV2JJ5EDN4G7GSW5NTBLDWWV5RKIIRBVZQNSSUTILLOHCR7MIDZRBM6SVUPHFL4LNSTB57P55THBGYMDBBGTZN6GA",
                  "https://www.microsoft.com/microsoft-365/roadmap?filters=\u0026searchterms=89132",
                  "https://urldefense.com/v3/__https://admin.microsoft.com/AdminPortal/home*/MessageCenter/:/messages/MC335277?MCLinkSource=MajorUpdate__;Iw!!DfHvcUuWuuyr!59KccvthRTpMtDxYKoVlj7vkYuvNxlupWAfAsARsKkR39KAwkJ6N8zIeBZK6WNPk$",
                  "https://docs.microsoft.com/azure/active-directory/enterprise-users/linkedin-integration",
                  "https://urldefense.com/v3/__https://docs.microsoft.com/azure/active-directory/users-groups-roles/linkedin-integration__;!!DfHvcUuWuuyr!59KccvthRTpMtDxYKoVlj7vkYuvNxlupWAfAsARsKkR39KAwkJ6N8zIeBU7Yqr-6$",
                  "https://docs.microsoft.com/azure/active-directory/users-groups-roles/linkedin-integration",
                  "https://go.microsoft.com/fwlink/?LinkId=521839",
                  "https://admin.microsoft.com/AdminPortal/home#/MessageCenter/:/messages/MC335277?MCLinkSource=MajorUpdate",
                  "https://urldefense.com/v3/__https://docs.microsoft.com/azure/active-directory/enterprise-users/linkedin-integration__;!!DfHvcUuWuuyr!59KccvthRTpMtDxYKoVlj7vkYuvNxlupWAfAsARsKkR39KAwkJ6N8zIeBdadrnub$",
                  "https://urldefense.com/v3/__https://go.microsoft.com/fwlink/?LinkId=521839__;!!DfHvcUuWuuyr!59KccvthRTpMtDxYKoVlj7vkYuvNxlupWAfAsARsKkR39KAwkJ6N8zIeBQQbTKa-$",
                  "http://www.w3.org/1999/xhtml",
                  "https://urldefense.com/v3/__https://docs.microsoft.com/en-us/microsoft-365/admin/manage/language-translation-for-message-center-posts?view=o365-worldwide__;!!DfHvcUuWuuyr!59KccvthRTpMtDxYKoVlj7vkYuvNxlupWAfAsARsKkR39KAwkJ6N8zIeBcMEwkML$",
                  "https://docs.microsoft.com/en-us/microsoft-365/admin/manage/language-translation-for-message-center-posts?view=o365-worldwide",
                  "https://img-prod-cms-rt-microsoft-com.akamaized.net/cms/api/am/imageFileData/RWWrZs?ver=3d7d",
                  "https://admin.microsoft.com/adminportal/home#/MessageCenter/:/mcpreferences",
                  "https://urldefense.com/v3/__https://www.microsoft.com/microsoft-365/roadmap?filters=\u0026searchterms=89132__;!!DfHvcUuWuuyr!59KccvthRTpMtDxYKoVlj7vkYuvNxlupWAfAsARsKkR39KAwkJ6N8zIeBTcv1yFl$"
               ]
            },
            {
               "abuseCopy": false,
               "body": "\u003c!DOCTYPE html\u003e\u003chtml xmlns=\"http://www.w3.org/1999/xhtml\"\u003e\u003chead\u003e\u003c!-- BaNnErBlUrFlE-HeAdEr-start --\u003e\u003cmeta http-equiv=\"Content-Type\" content=\"text/html; charset=utf-8\"\u003e\u003cmeta name=\"viewport\" content=\"width=device-width, initial-scale=1.0\"\u003e\u003cstyle\u003e\n      .pfptBannerTableMSO { padding: 0px 12px 5px 12px; width: 100%;border-radius:4px;border-top:4px solid #90a4ae;background-color:#D0D8DC; }\n      .pfptTitleMSO { color:#000000 !important;font-family: 'Arial', sans-serif !important;font-weight:bold !important;font-size:14px !important; }\n      .pfptSubtitleMSO { font-size:12px !important; font-family: 'Arial', sans-serif !important; }\n      .pfptButtonMSO { mso-padding-alt: 7.5px; padding: 7.5px; text-decoration: none; font-family: 'Arial', sans-serif !important; font-size: 14px; line-height: 40px; border-radius:2px; }\n      .pfptPrimaryButtonMSO {\n\tborder: 1.5px solid #666666; color: #000000;\n      }\n     .pfptBanner {\n\tmargin: 15px 14px 30px 14px;\n\tpadding: 8px 16px 8px 16px;\n\tborder-radius: 4px;\n\tmin-width: 200px;\n\tbackground-color: #D0D8DC;\n\tborder-top: 4px solid #90a4ae;\n      }\n      .pfptBannerTitle {\n\tcolor: #000000;\n\tfont-family: 'Arial', sans-serif;\n\tfont-size: 14px;\n\tfont-weight: bold;\n\tline-height: 18px;\n\tdisplay: block;\n      }\n      .pfptBannerSubtitle {\n\tcolor: #000000;\n\tfont-weight: normal;\n\tfont-family: 'Arial', sans-serif;\n\tfont-size: 12px;\n\tline-height: 18px;\n\tmargin-top: 2px;\n\tdisplay: block;\n      }\n      .pfptButton {\n\tdisplay: inline-block;\n\tfont-family: 'Arial', sans-serif;\n\tfont-size: 14px;\n\tfont-weight: normal;\n\tborder-radius: 2px;\n\tpadding: 7.5px 16px;\n\tmargin: 3px 0 3px 16px;\n\twhite-space: nowrap;\n\twidth: fit-content;\n      }\n      .pfptPrimaryButton {\n\tborder: 1px solid #666666;\n      }\n      .pfptPrimaryButton:hover, .pfptPrimaryButton:focus {\n\tbackground-color: #b4c1c7;\n      }\n      .pfptPrimaryButton:active {\n\tbackground-color: #90a4ae;\n      }\n      .pfptMessageContainer {\n\tdisplay: inline-block;\n\tmargin: 0px 0px 1px 0px;\n\tmax-width: 600px;\n      }\n      .pfptButtonGroup {\n\tfloat: right;\n\tmargin: 0px 0px 0px 16px;\n\ttext-align: right;\n\twidth: fit-content;\n      }\n      .pfptPreheader { display:none !important; visibility:hidden; mso-hide:all; font-size:1px; line-height:1px; max-height:0px; max-width:0px; opacity:0; overflow:hidden; }\u003c/style\u003e\u003c!-- BaNnErBlUrFlE-HeAdEr-end --\u003e\u003cmeta name=\"viewport\" content=\"width=device-width, initial-scale=1\"\u003e\u003cmeta http-equiv=\"X-UA-Compatible\" content=\"IE=edge\"\u003e\u003cstyle\u003e\n            body, table, td { font-family: Segoe UI, Helvetica, Arial, sans-serif !important; }\n            a { color: #006CBE; text-decoration: none; }\u003c/style\u003e\u003c/head\u003e\u003cbody\u003e\u003c!-- BaNnErBlUrFlE-BoDy-start --\u003e\u003c!-- Preheader Text : BEGIN --\u003e\u003cspan class=\"pfptPreheader\" style=\"display:none !important;visibility:hidden;mso-hide:all;font-size:1px;color:#ffffff;line-height:1px;max-height:0px;max-width:0px;opacity:0;overflow:hidden;\"\u003e‍ ‍ ‍ ‍ ‍ ‍ ‍ ‍ ‍ ‍ ‍ ‍ ‍ ‍ ‍ ‍ ‍ ‍ ‍ ‍ ‍ ‍ ‍ ‍ ‍ ‍ ‍ ‍ ‍ ‍ ‍ ‍ ‍ ‍ ‍ ‍ ‍ ‍ ‍ ‍ ‍ ‍ ‍ ‍ ‍ ‍ ‍ ‍ ‍ ‍ ‍ ‍ ‍ ‍ ‍ ‍ ‍ ‍ ‍ ‍ ‍ ‍ ‍ ‍ ‍ ‍ ‍ ‍ ‍ ‍ ‍ ‍ ‍ ‍ ‍ ‍ ‍ ‍ ‍ ‍ ‍ ‍ ‍ ‍ ‍ ‍ ‍ ‍ ‍ ‍ ‍ ‍ ‍ ‍ ‍ ‍ ‍ ‍ ‍ ‍ ‍ ‍ ‍ ‍ ‍ ‍ ‍ ‍ ‍ ‍ ‍ ‍ ‍ ‍ ‍ ‍ ‍ ‍ ‍ ‍ ‍ ‍ ‍ ‍ ‍ ‍ ‍ ‍ ‍ ‍ ‍ ‍ ‍ ‍ ‍ ‍ ‍ ‍ ‍ ‍ ‍ ‍ ‍ ‍ ‍ ‍ ‍ ‍ ‍ ‍ ‍ ‍ ‍ ‍ ‍ ‍ ‍ ‍ ‍ ‍ ‍ ‍ ‍ ‍ ‍ ‍ ‍ ‍ ‍ ‍ ‍ ‍ ‍ ‍ ‍ ‍ ‍ ‍ ‍ ‍ ‍ ‍ ‍ ‍ ‍ ‍ ‍ ‍ ‍ ‍ ‍ ‍ ‍ ‍ ‍ ‍ ‍ ‍ ‍ ‍ ‍ ‍ ‍ ‍ ‍ ‍ ‍ ‍ ‍ ‍ ‍ ‍ ‍ ‍ ‍ ‍ ‍ ‍ ‍ ‍ ‍ ‍ ‍ ‍ ‍ ‍ ‍ ‍ ‍ ‍ ‍ ‍ ‍ ‍ ‍ ‍ ‍ ‍ ‍ \u003c/span\u003e\u003c!-- Preheader Text : END --\u003e\u003c!-- Email Banner : BEGIN --\u003e\u003cspan style=\"display:none !important;visibility:hidden;mso-hide:all;font-size:1px;color:#ffffff;line-height:1px;max-height:0px;max-width:0px;opacity:0;overflow:hidden;\"\u003eZjQcmQRYFpfptBannerStart\u003c/span\u003e\u003c!--[if ((ie)|(mso))]\u003e\u003ctable border=\"0\" cellspacing=\"0\" cellpadding=\"0\" width=\"100%\" style=\"padding: 3px 0px 16px 0px; direction: ltr\" \u003e\u003ctr\u003e\u003ctd\u003e\u003ctable class=\"pfptBannerTableMSO\" border=\"0\" cellspacing=\"0\" cellpadding=\"0\" style=\"padding: 0px 10px 5px 6px; width: 100%;border-radius:4px;border-top:4px solid #90a4ae;background-color:#D0D8DC;\"\u003e\u003ctr\u003e\u003ctd valign=\"top\"\u003e\u003ctable align=\"left\" border=\"0\" cellspacing=\"0\" cellpadding=\"0\" style=\"padding: 4px 8px 4px 8px\"\u003e\u003ctr\u003e\u003ctd\u003e\u003cspan class=\"pfptTitleMSO\" style=\"color:#000000 !important;font-family: 'Arial', sans-serif;font-weight:bold !important;font-size:14px !important; direction: ltr\"\u003e\n\t  This Message Is From an External Sender\u003c/span\u003e\u003c/td\u003e\u003c/tr\u003e\u003ctr\u003e\u003ctd\u003e\u003cspan class=\"pfptSubtitleMSO\" style=\"color:#000000 !important;font-weight:normal !important;font-family: 'Arial', sans-serif; font-size:12px !important; direction: ltr\"\u003e\n          This message came from outside your organization.\u003c/span\u003e\u003c/td\u003e\u003c/tr\u003e\u003c/table\u003e\u003c/td\u003e\u003c/tr\u003e\u003c/table\u003e\u003c/td\u003e\u003c/tr\u003e\u003c/table\u003e\u003c![endif]--\u003e\u003c![if !((ie)|(mso))]\u003e\u003cdiv dir=\"ltr\" class=\"pfptBanner\" style=\"margin:16px 0px 16px 0px; padding:8px 16px 8px 16px; border-radius: 4px; min-width: 200px;background-color: #D0D8DC; border-top: 4px solid #90a4ae;\"\u003e\u003cdiv class=\"pfptMessageContainer\" style=\"display: inline-block; margin: 0px 0px 1px 0px; max-width: 600px;\"\u003e\u003cdiv class=\"pfptBannerTitle\" style=\"color:#000000 !important;font-family: 'Arial', sans-serif !important;font-weight:bold !important;font-size:14px !important;line-height:18px;display:block;\"\u003eThis Message Is From an External Sender \u003c/div\u003e\u003cdiv class=\"pfptBannerSubtitle\" style=\"color:#000000 !important;font-weight:normal !important;font-family: 'Arial', sans-serif !important;font-size:12px !important;line-height:18px;margin-top:2px;display:block\"\u003eThis message came from outside your organization. \u003c/div\u003e\u003c/div\u003e\u003c/div\u003e\u003c![endif]\u003e\u003cdiv style=\"display:none !important;visibility:hidden;mso-hide:all;font-size:1px;color:#ffffff;line-height:1px;max-height:0px;max-width:0px;opacity:0;overflow:hidden;\"\u003eZjQcmQRYFpfptBannerEnd\u003c/div\u003e\u003c!-- Email Banner : END --\u003e\u003c!-- BaNnErBlUrFlE-BoDy-end --\u003e\u003c!-- Outer wrapper --\u003e\u003cdiv style=\"background: white; min-height: 100vh; color: #323130; font-size: 14px;\"\u003e\u003ctable border=\"0\" cellpadding=\"0\" cellspacing=\"0\" width=\"100%\" height=\"100%\"\u003e\u003ctbody\u003e\u003ctr\u003e\u003ctd\u003e\u003c/td\u003e\u003ctd width=\"640\"\u003e\u003c!-- Inner wrapper --\u003e\u003ctable border=\"0\" cellpadding=\"0\" cellspacing=\"0\" style=\"min-width: 100%; background: white;\"\u003e\u003c!-- Logo --\u003e\u003ctbody\u003e\u003ctr\u003e\u003ctd style=\"padding: 24px 24px 45px;\"\u003e\u003cimg src=\"https://eus-contentstorage.osi.office.net/images/retailer.images/centralizeddeployment/logos/112fec798b78aa02.png\" width=\"100\" height=\"21\" alt=\"Microsoft\"\u003e\u003c/td\u003e\u003c/tr\u003e\u003c!-- Title --\u003e\u003ctr\u003e\u003ctd style=\"font-size: 28px; padding: 0 24px; font-weight: bold; color: #000000\"\u003eLinkedIn Integration coming to Teams\u003c/td\u003e\u003c/tr\u003e\u003c!-- Sub-header / Company name --\u003e\u003ctr\u003e\u003ctd style=\"color: #323130; padding: 20px 24px 40px 24px;\"\u003e\u003cspan style=\"font-weight: 600\"\u003eMC335277 · PFPT100\u003c/span\u003e\u003c/td\u003e\u003c/tr\u003e\u003c!-- Main content --\u003e\u003ctr\u003e\u003ctd style=\"padding: 0 24px 44px;\"\u003e\u003cdiv\u003e\u003cp style=\"margin-top: 0\"\u003eFor those tenants that have LinkedIn integration available to their members, we are expanding its availability to Teams as a panel in one on one conversations. This is the first part of a series of updates which will also bring LinkedIn to the contact card in the coming months.\u0026nbsp; Initially this is limited to contacts within the tenant, but as the contact card updates are released, then this will be available for all contacts within and outside the tenant.\u003cbr\u003e\u003c/p\u003e\u003cp\u003eThis message is associated with Microsoft 365 Roadmap ID \u003ca href=\"https://urldefense.com/v3/__https://www.microsoft.com/microsoft-365/roadmap?filters=\u0026amp;searchterms=89132__;!!DfHvcUuWuuyr!59KccvthRTpMtDxYKoVlj7vkYuvNxlupWAfAsARsKkR39KAwkJ6N8zIeBTcv1yFl$\" target=\"_blank\"\u003e89132\u003c/a\u003e\u003cbr\u003e\u003c/p\u003e\u003cp\u003e\u003cb style=\"font-weight: 600\"\u003eWhen this will happen:\u003c/b\u003e\u003cbr\u003e\u003c/p\u003e\u003cp\u003eWe will begin rolling this out in mid-March and expect to complete by early April.\u003c/p\u003e\u003cp\u003e\u003cb style=\"font-weight: 600\"\u003eHow this will affect your organization:\u003c/b\u003e\u003cbr\u003e\u003c/p\u003e\u003cp\u003eOnce available, the new LinkedIn tab will appear at the top of the 1:1 conversation in Teams alongside the existing tabs for Chat, Files, Organization and Activity, and will work just like the contact card in Outlook does today.\u003c/p\u003e\u003cp\u003e\u003cimg src=\"https://img-prod-cms-rt-microsoft-com.akamaized.net/cms/api/am/imageFileData/RWWrZs?ver=3d7d\" alt=\"LinkedIn Menu Option\" width=\"400\" height=\"\"\u003e\u003c/p\u003e\u003cp\u003eYou continue to have the same controls as before over the integration availability.\u0026nbsp; This is just making the experience available in more places for your members.\u003c/p\u003e\u003cp\u003e\u003cb style=\"font-weight: 600\"\u003eWhat you need to do to prepare:\u003c/b\u003e\u003c/p\u003e\u003cp\u003e\u003c/p\u003e\u003cp\u003eReview your current configuration to ensure the appropriate experience for your organization.\u003c/p\u003e\u003cp\u003eTo learn about existing controls, review:\u0026nbsp;\u003ca href=\"https://urldefense.com/v3/__https://docs.microsoft.com/azure/active-directory/users-groups-roles/linkedin-integration__;!!DfHvcUuWuuyr!59KccvthRTpMtDxYKoVlj7vkYuvNxlupWAfAsARsKkR39KAwkJ6N8zIeBU7Yqr-6$\" target=\"_blank\"\u003eIntegrate LinkedIn account connections in Azure Active Directory\u003c/a\u003e\u003c/p\u003e\u003ca href=\"https://urldefense.com/v3/__https://docs.microsoft.com/azure/active-directory/enterprise-users/linkedin-integration__;!!DfHvcUuWuuyr!59KccvthRTpMtDxYKoVlj7vkYuvNxlupWAfAsARsKkR39KAwkJ6N8zIeBdadrnub$\" title=\"Additional Information\"\u003eAdditional Information\u003c/a\u003e\u003c/div\u003e\u003cdiv style=\"padding-top: 3px\"\u003e\u003ca href=\"https://urldefense.com/v3/__https://admin.microsoft.com/AdminPortal/home*/MessageCenter/:/messages/MC335277?MCLinkSource=MajorUpdate__;Iw!!DfHvcUuWuuyr!59KccvthRTpMtDxYKoVlj7vkYuvNxlupWAfAsARsKkR39KAwkJ6N8zIeBZK6WNPk$\" title=\"view message\" target=\"_blank\"\u003eView this message in the Microsoft 365 admin center\u003c/a\u003e\u003c/div\u003e\u003c/td\u003e\u003c/tr\u003e\u003c!-- Footer --\u003e\u003ctr\u003e\u003ctd\u003e\u003ctable border=\"0\" cellpadding=\"0\" cellspacing=\"0\" width=\"100%\" style=\"min-width: 100%; background-color: #F3F2F1;\"\u003e\u003c!-- Disclaimer --\u003e\u003ctbody\u003e\u003ctr\u003e\u003ctd style=\"padding: 44px 24px 3px; font-size: 10px; color: #484644\"\u003eYou're subscribed to this email using abuse@pfpt100.com. If you're an IT admin, you're subscribed by default, but you can \u003ca href=\"https://urldefense.com/v3/__https://admin.microsoft.com/adminportal/home*/MessageCenter/:/mcpreferences__;Iw!!DfHvcUuWuuyr!59KccvthRTpMtDxYKoVlj7vkYuvNxlupWAfAsARsKkR39KAwkJ6N8zIeBRxCf0F6$\" target=\"_blank\"\u003eunsubscribe at any time\u003c/a\u003e. If you're not an IT admin, ask your admin to remove your email address from Microsoft 365 message center preferences.\u003cbr\u003e\u003cbr\u003e\u003ca href=\"https://urldefense.com/v3/__https://docs.microsoft.com/en-us/microsoft-365/admin/manage/language-translation-for-message-center-posts?view=o365-worldwide__;!!DfHvcUuWuuyr!59KccvthRTpMtDxYKoVlj7vkYuvNxlupWAfAsARsKkR39KAwkJ6N8zIeBcMEwkML$\" target=\"_blank\"\u003eHow to view translated messages\u003c/a\u003e\u003cbr\u003e\u003c/td\u003e\u003c/tr\u003e\u003ctr\u003e\u003ctd style=\"padding: 25px 24px 24px; font-size: 12px\"\u003e\u003ca href=\"https://urldefense.com/v3/__https://go.microsoft.com/fwlink/?LinkId=521839__;!!DfHvcUuWuuyr!59KccvthRTpMtDxYKoVlj7vkYuvNxlupWAfAsARsKkR39KAwkJ6N8zIeBQQbTKa-$\" target=\"_blank\" style=\"color:#696969; text-decoration: underline; text-decoration-color:#696969;\"\u003ePrivacy statement\u003c/a\u003e\u003cdiv style=\"color:#696969; margin-top: 10px; margin-bottom: 13px;\"\u003eMicrosoft Corporation, One Microsoft Way, Redmond WA 98052 USA\u003c/div\u003e\u003cimg src=\"https://eus-contentstorage.osi.office.net/images/retailer.images/centralizeddeployment/logos/112fec798b78aa02.png\" width=\"94\" height=\"20\" alt=\"Microsoft\"\u003e\u003c/td\u003e\u003c/tr\u003e\u003c/tbody\u003e\u003c/table\u003e\u003c/td\u003e\u003c/tr\u003e\u003c/tbody\u003e\u003c/table\u003e\u003c/td\u003e\u003ctd\u003e\u003c/td\u003e\u003c/tr\u003e\u003c/tbody\u003e\u003c/table\u003e\u003c/div\u003e\u003cimg src=\"https://mucp.api.account.microsoft.com/m/v2/v?d=AIAADI7YL2B6SL73WAMTS4CDGZ7UVQ7R2A6SKP6364LWPPIAWBPBRH2QCJXT6KTC4AAWU26UZOXKTC3VBVHZF4OFXKB4TNO3WFIAN44NLTBD3PFKN36UC5KFMD6C2DN2XJQLCWH4N2DUM2R4X42JWRRE2R2PWSQ\u0026amp;i=AIAACTHRJJBNYIMYGIMEHWP3B3PWP7AFJEQ2QHM2FAH5RBIK2QJAYECEKFRJOWQQZTMWMH7VDMCWYSRZVSS3Q4FZX4CAI6DLLG5ZCFRG56GUVZVF3AH2Z3XMF7UD4C3H62IWSSHX4KNVLWDJ5BBSL4VZQMPI24BCEC47EZV4KBRWGQ5GUY5NW47TQ6BMCFB7QZ3Q56SV2JJ5EDN4G7GSW5NTBLDWWV5RKIIRBVZQNSSUTILLOHCR7MIDZRBM6SVUPHFL4LNSTB57P55THBGYMDBBGTZN6GA\" width=\"1\" height=\"1\" tabindex=\"-1\" aria-hidden=\"true\" alt=\"\"\u003e\u003c!-- cV: WnAB9MEIgUagZxCK.4.1.1.4 --\u003e\u003c/body\u003e\u003c/html\u003e",
               "bodyType": "html",
               "headers": {
                  "Authentication-Results": "spf=fail (sender IP is 205.220.168.64) smtp.mailfrom=microsoft.com; dkim=fail (body hash did not verify) header.d=microsoft.com;dmarc=fail action=oreject header.from=microsoft.com;compauth=none reason=451",
                  "Authentication-Results-Original": "ppops.net;\tspf=pass smtp.mailfrom=o365mc@microsoft.com;\tdkim=pass header.d=microsoft.com header.s=s1024",
                  "Content-Transfer-Encoding": "quoted-printable",
                  "Content-Type": "text/html",
                  "DKIM-Signature": "v=1; a=rsa-sha256; c=relaxed/relaxed; d=microsoft.com; s=s1024; t=1645681862; h=From; bh=Nhbt7oE7lCdk+GeafjQvVqz1UUHRv+A4z6/QHcm x/yg=; b=Unu/oEpugNrYw1wAX8441KziXlJb/25i5Xf9W8icrSUdbb83RQD4iM4CpUNgZcBY PDdqKiVV0eufQjlWIi1rKE9Kd8fNoaslaNQubu0t9sWCYWQ2Z6Z0Yg9CoHmhbG0FyDKeAh3Ao dGCpQydW7AtVidGdpW4x9VFMx0R6O32z6E=;",
                  "Date": "Wed, 23 Feb 2022 21:51:02 -0800",
                  "MIME-Version": "1.0",
                  "Message-ID": "\u003ce47eea564f8140198987e9c726ba14e7-JFBVALKQOJXWILKNK4YVA7CPGM3DKTLFONZWCZ3FINSW45DFOJ6E2ZLTONQWOZKDMVXHIZLSL5GUGMZTGUZDON34KNWXI4A=@microsoft.com\u003e",
                  "Received": "from smtpi.msn.com (eus-irissmtp10.msn.com [52.234.172.105])\tby mx0a-006af001.pphosted.com (PPS) with ESMTPS id 3ed6cqrbf8-1\t(version=TLSv1.2 cipher=ECDHE-RSA-AES256-SHA384 bits=256 verify=NOT)\tfor \u003cabuse@pfpt100.com\u003e; Thu, 24 Feb 2022 05:51:04 +0000",
                  "Received-SPF": "Fail (protection.outlook.com: domain of microsoft.com does not designate 205.220.168.64 as permitted sender) receiver=protection.outlook.com; client-ip=205.220.168.64; helo=mx0a-006af001.pphosted.com;",
                  "Return-Path": "o365mc@microsoft.com",
                  "Subject": "Major update from Message center",
                  "X-DKIM-Signer": "DkimX (v3.20.320)",
                  "X-EOPAttributedMessage": "0",
                  "X-EOPTenantAttributedMessage": "2bac89e1-0311-4f18-bbb5-a229530a794a:0",
                  "X-Forefront-Antispam-Report": "CIP:205.220.168.64;CTRY:US;LANG:en;SCL:1;SRV:;IPV:NLI;SFV:NSPM;H:mx0a-006af001.pphosted.com;PTR:mx0a-006af001.pphosted.com;CAT:NONE;SFS:(13230001)(47530400004)(76236003)(7636003)(7596003)(336012)(8676002)(2616005)(956004)(26005)(166002)(356005)(10290500003)(5660300002)(19627235002)(36756003)(15650500001)(52230400001)(19627405001)(83380400001)(86362001)(6916009)(1096003)(18121605002)(15585785002);DIR:INB;",
                  "X-MS-Exchange-CrossTenant-AuthAs": "Anonymous",
                  "X-MS-Exchange-CrossTenant-AuthSource": "MW2NAM12FT042.eop-nam12.prod.protection.outlook.com",
                  "X-MS-Exchange-CrossTenant-FromEntityHeader": "Internet",
                  "X-MS-Exchange-CrossTenant-Id": "2bac89e1-0311-4f18-bbb5-a229530a794a",
                  "X-MS-Exchange-CrossTenant-Network-Message-Id": "fbd1cbcb-a1f8-455e-a0a2-08d9f759a60a",
                  "X-MS-Exchange-CrossTenant-OriginalArrivalTime": "24 Feb 2022 05:51:05.7937 (UTC)",
                  "X-MS-Exchange-Organization-AuthAs": "Anonymous",
                  "X-MS-Exchange-Organization-AuthSource": "MW2NAM12FT042.eop-nam12.prod.protection.outlook.com",
                  "X-MS-Exchange-Organization-ExpirationInterval": "1:00:00:00.0000000",
                  "X-MS-Exchange-Organization-ExpirationIntervalReason": "OriginalSubmit",
                  "X-MS-Exchange-Organization-ExpirationStartTime": "24 Feb 2022 05:51:05.9500 (UTC)",
                  "X-MS-Exchange-Organization-ExpirationStartTimeReason": "OriginalSubmit",
                  "X-MS-Exchange-Organization-MessageDirectionality": "Incoming",
                  "X-MS-Exchange-Organization-Network-Message-Id": "fbd1cbcb-a1f8-455e-a0a2-08d9f759a60a",
                  "X-MS-Exchange-Organization-SCL": "1",
                  "X-MS-Exchange-Processed-By-BccFoldering": "15.20.5017.024",
                  "X-MS-Exchange-Transport-CrossTenantHeadersStamped": "PH0PR14MB4328",
                  "X-MS-Exchange-Transport-EndToEndLatency": "00:00:02.4511501",
                  "X-MS-Iris-MetaData": "{\"Type\":null,\"Fields\":{\"InstanceID\":\"e47eea56-4f81-4019-8987-e9c726ba14e7\",\"ActivityID\":\"aa930d28-10ac-40da-b06d-52a4b3208dfd\"}}",
                  "X-MS-Office365-Filtering-Correlation-Id": "fbd1cbcb-a1f8-455e-a0a2-08d9f759a60a",
                  "X-MS-PublicTrafficType": "Email",
                  "X-MS-TrafficTypeDiagnostic": "PH0PR14MB4328:EE_",
                  "X-Microsoft-Antispam": "BCL:0;",
                  "X-Microsoft-Antispam-Mailbox-Delivery": "ucf:0;jmr:0;auth:0;dest:I;ENG:(910001)(944506458)(944626604)(920097)(930097);",
                  "X-Microsoft-Antispam-Message-Info": "0x0hRs3JpZozx6KhfwfiH6k/erAsVl2qJEArW7zq/uK+OCIPwxFDdlBTqkMr4bLAn4V9ajIXdE/Q9/hatWWl/TH4X/Wjb99WHUOtoHUi8MAmtCJvznd7xbF9PK7yS9+4csOboX5wDv/R7H+yuE/c6qRKNsiOIVD0c+V1o4cqK4sYYLrzFmODGpHlD2iZj063GVKpOSle8HRRIWu7xMWBez9/yrAJrcLlcUhDF/YA1aPZYUSQzuzlp04Dq9rGrTyi/gUnwIQu/nJOk6Et+Wj4MPPdKTy0drUh7m+2cBGHSQ5vtRo6abPDeKPPLtXiWlQ6wYAcY2VZE4czJrUFLTzJs5MV5G31Z0UbMwavs++K4y70+r9Rcskoi9yKl8TUIEuP94kgdGTR5uJg26CGkGxHRLnWD8uJi0PC8b2SStCbMYfc0IMHgK0tJTo7nZ/82En7SeKVxwCanZPAeVUpIntMyQ2HkUGqR9bFWlCuV9wTdjOQ88zNX4HqhQCbsP9USMeNiL/bIpdI7XDwBb84lPQuG8nTtv1up05ZBKIu5jDf9JsPIdy1HEFC5EiV1kvxui7SbjPGeMoRbm60Wpb/B5pJg4qHiC1SAL2cpaz1v7lx5aGgaleSm656euXxn+iv1VquBqhplSMe6+5opTG2X+g+/2076u2wymmtQ7vNSect9iuI3wP9dgVLyWIUiQwEN9sIotKXth168NKwQxDqfALnbNllDlxly+B+GWx+Wt6poiqxsoymzDqd9kWNHQ89jE0JZ6cZ002OsSCyJVOhxRvE7IxmGtWFZerlnvokPdGdmrSdyu/DTYSbw1KPqoMuWLqp3nqAiDG9eR3a9QkpLXb3ZpQQqx3oqhcZQ5lXLvMKWzpE7R1cO9r7GTg3/x5N969Glf8/5BL7fRDoVHx71MOCznMj99wdA7nwnmpntm0Vg5PgRzfFX05klzPNzaCXAFjVaRpiGxgde0z/oSvbUKuzgBRLGGn2G77bBoumdjZoDWimYphDMm5c6zXy/6N4Wd93JBwDuhlndAHKMrakUzd/HD4MaN11Z4J6dUFq12Xw4p9Tj67jx/+Cybl82oa3TUpA65oMcH2FYC9cwxJb2HrYEp/Aa+zU3HXDsFDJO6fomlii4xhOpaRfrk8wJZ8VpObxQUMcTXxUTUVmreLMFqqW+2VT2C2Gq4Eg4D15IgdqKb6h5wTkcvEJve7va/Hv0XEDElIky/DRVLAtwqrNnBqMJl+/HbDHUHXF7KxydRxdxN5LsI1C67eZjCvrEwRbEQHTVf5BXtAPOXxeiUuWDx/+7EVfwA3EFJ2+NoLtdESfbVQ7Z6gNOak5MIWJLetdj+GM4fGe+PbioCjIkCDVLV4pc6kXPo8ydsmlKEtdvdPcrqN/RVp7LJ90f5DmEUYoN15lulaaOnJU+ygrLILtZ42OqxBEblbMDbEWsSrfK1suaKaJbZSYNcV3aSFfMQBQtISEhGDmtvo46mct2WJ6dRF44dPL3lICzZc48hdLEqS259WmUiAAl7l5NCBy/RPlQnb1wCbYczWF85U23/dADAylmGcMKDnAtRg3P69ioj7fr7shaKlRNfWdBw2FkR+GbnYvcKvq+rlF7U34mvpaj5AnTji6BnB1EdhwN1HqkfY1kqsANMyX0BgK/DT24az90Un6wzM1+B/EC120zHhLTT4JF1KOtLtRUa0LL0CHA4/x5XAIrP+R4saaYNSO7HHpC+W13aYloY11/KoswhdUsz4gC8Vb4d57Svo4nFRfqk5PqW31McKghUDFIyybK0TgxeNu8zABwwBYzLVy172kp1WJ563dXopMluKMUeBqLxhHIQskijhG6LZ2usXPrJHZLtKqHqGWwHvRhIj77HrxdBG9LnfHDXsMXvJ+1y+VAe+CBEdoNdmcA1UCUBs9tb6702hX",
                  "X-Proofpoint-Banner-Trigger": "inbound",
                  "X-Proofpoint-GUID": "ZB-_fnEzClOzeq2x42K25pTaOiBejTor",
                  "X-Proofpoint-ORIG-GUID": "ZB-_fnEzClOzeq2x42K25pTaOiBejTor",
                  "X-Proofpoint-Spam-Details": "rule=notspam policy=default score=0 bulkscore=0 mlxlogscore=613 suspectscore=0 phishscore=0 mlxscore=0 adultscore=0 malwarescore=0 spamscore=0 classifier=spam adjust=0 reason=mlx scancount=1 engine=8.12.0-2201110000 definitions=main-2202240033",
                  "X-Proofpoint-Virus-Version": "vendor=baseguard engine=ICAP:2.0.205,Aquarius:18.0.816,Hydra:6.0.425,FMLib:17.11.64.514 definitions=2022-02-23_09,2022-02-23_01,2022-02-23_01"
               },
               "messageId": "\u003ce47eea564f8140198987e9c726ba14e7-JFBVALKQOJXWILKNK4YVA7CPGM3DKTLFONZWCZ3FINSW45DFOJ6E2ZLTONQWOZKDMVXHIZLSL5GUGMZTGUZDON34KNWXI4A=@microsoft.com\u003e",
               "recipient": {
                  "email": "abuse@pfpt100.com",
                  "vap": false
               },
               "sender": {
                  "email": "o365mc@microsoft.com",
                  "vap": false
               },
               "subject": "Major update from Message center",
               "urls": [
                  "https://urldefense.com/v3/__https://admin.microsoft.com/adminportal/home*/MessageCenter/:/mcpreferences__;Iw!!DfHvcUuWuuyr!59KccvthRTpMtDxYKoVlj7vkYuvNxlupWAfAsARsKkR39KAwkJ6N8zIeBRxCf0F6$",
                  "https://eus-contentstorage.osi.office.net/images/retailer.images/centralizeddeployment/logos/112fec798b78aa02.png",
                  "https://mucp.api.account.microsoft.com/m/v2/v?d=AIAADI7YL2B6SL73WAMTS4CDGZ7UVQ7R2A6SKP6364LWPPIAWBPBRH2QCJXT6KTC4AAWU26UZOXKTC3VBVHZF4OFXKB4TNO3WFIAN44NLTBD3PFKN36UC5KFMD6C2DN2XJQLCWH4N2DUM2R4X42JWRRE2R2PWSQ\u0026i=AIAACTHRJJBNYIMYGIMEHWP3B3PWP7AFJEQ2QHM2FAH5RBIK2QJAYECEKFRJOWQQZTMWMH7VDMCWYSRZVSS3Q4FZX4CAI6DLLG5ZCFRG56GUVZVF3AH2Z3XMF7UD4C3H62IWSSHX4KNVLWDJ5BBSL4VZQMPI24BCEC47EZV4KBRWGQ5GUY5NW47TQ6BMCFB7QZ3Q56SV2JJ5EDN4G7GSW5NTBLDWWV5RKIIRBVZQNSSUTILLOHCR7MIDZRBM6SVUPHFL4LNSTB57P55THBGYMDBBGTZN6GA",
                  "https://www.microsoft.com/microsoft-365/roadmap?filters=\u0026searchterms=89132",
                  "https://urldefense.com/v3/__https://admin.microsoft.com/AdminPortal/home*/MessageCenter/:/messages/MC335277?MCLinkSource=MajorUpdate__;Iw!!DfHvcUuWuuyr!59KccvthRTpMtDxYKoVlj7vkYuvNxlupWAfAsARsKkR39KAwkJ6N8zIeBZK6WNPk$",
                  "https://docs.microsoft.com/azure/active-directory/enterprise-users/linkedin-integration",
                  "https://urldefense.com/v3/__https://docs.microsoft.com/azure/active-directory/users-groups-roles/linkedin-integration__;!!DfHvcUuWuuyr!59KccvthRTpMtDxYKoVlj7vkYuvNxlupWAfAsARsKkR39KAwkJ6N8zIeBU7Yqr-6$",
                  "https://docs.microsoft.com/azure/active-directory/users-groups-roles/linkedin-integration",
                  "https://go.microsoft.com/fwlink/?LinkId=521839",
                  "https://admin.microsoft.com/AdminPortal/home#/MessageCenter/:/messages/MC335277?MCLinkSource=MajorUpdate",
                  "https://urldefense.com/v3/__https://docs.microsoft.com/azure/active-directory/enterprise-users/linkedin-integration__;!!DfHvcUuWuuyr!59KccvthRTpMtDxYKoVlj7vkYuvNxlupWAfAsARsKkR39KAwkJ6N8zIeBdadrnub$",
                  "https://urldefense.com/v3/__https://go.microsoft.com/fwlink/?LinkId=521839__;!!DfHvcUuWuuyr!59KccvthRTpMtDxYKoVlj7vkYuvNxlupWAfAsARsKkR39KAwkJ6N8zIeBQQbTKa-$",
                  "http://www.w3.org/1999/xhtml",
                  "https://urldefense.com/v3/__https://docs.microsoft.com/en-us/microsoft-365/admin/manage/language-translation-for-message-center-posts?view=o365-worldwide__;!!DfHvcUuWuuyr!59KccvthRTpMtDxYKoVlj7vkYuvNxlupWAfAsARsKkR39KAwkJ6N8zIeBcMEwkML$",
                  "https://docs.microsoft.com/en-us/microsoft-365/admin/manage/language-translation-for-message-center-posts?view=o365-worldwide",
                  "https://img-prod-cms-rt-microsoft-com.akamaized.net/cms/api/am/imageFileData/RWWrZs?ver=3d7d",
                  "https://admin.microsoft.com/adminportal/home#/MessageCenter/:/mcpreferences",
                  "https://urldefense.com/v3/__https://www.microsoft.com/microsoft-365/roadmap?filters=\u0026searchterms=89132__;!!DfHvcUuWuuyr!59KccvthRTpMtDxYKoVlj7vkYuvNxlupWAfAsARsKkR39KAwkJ6N8zIeBTcv1yFl$"
               ]
            }
         ],
         "falsePositive": false,
         "id": 1276,
         "received": "2022-02-24T05:51:58Z",
         "severity": "Info",
         "source": "Abuse o365",
         "state": "Linked"
      }
   ],
   "failed_quarantines": 0,
   "false_positive_count": 0,
   "hosts": {
      "url": [
         "https://urldefense.com/v3/__https://admin.microsoft.com/adminportal/home*/MessageCenter/:/mcpreferences__;Iw!!DfHvcUuWuuyr!59KccvthRTpMtDxYKoVlj7vkYuvNxlupWAfAsARsKkR39KAwkJ6N8zIeBRxCf0F6$",
         "https://www.microsoft.com/microsoft-365/roadmap?filters=\u0026searchterms=89132",
         "https://mucp.api.account.microsoft.com/m/v2/v?d=AIAADI7YL2B6SL73WAMTS4CDGZ7UVQ7R2A6SKP6364LWPPIAWBPBRH2QCJXT6KTC4AAWU26UZOXKTC3VBVHZF4OFXKB4TNO3WFIAN44NLTBD3PFKN36UC5KFMD6C2DN2XJQLCWH4N2DUM2R4X42JWRRE2R2PWSQ\u0026i=AIAACTHRJJBNYIMYGIMEHWP3B3PWP7AFJEQ2QHM2FAH5RBIK2QJAYECEKFRJOWQQZTMWMH7VDMCWYSRZVSS3Q4FZX4CAI6DLLG5ZCFRG56GUVZVF3AH2Z3XMF7UD4C3H62IWSSHX4KNVLWDJ5BBSL4VZQMPI24BCEC47EZV4KBRWGQ5GUY5NW47TQ6BMCFB7QZ3Q56SV2JJ5EDN4G7GSW5NTBLDWWV5RKIIRBVZQNSSUTILLOHCR7MIDZRBM6SVUPHFL4LNSTB57P55THBGYMDBBGTZN6GA",
         "https://eus-contentstorage.osi.office.net/images/retailer.images/centralizeddeployment/logos/112fec798b78aa02.png",
         "https://docs.microsoft.com/azure/active-directory/enterprise-users/linkedin-integration",
         "https://urldefense.com/v3/__https://admin.microsoft.com/AdminPortal/home*/MessageCenter/:/messages/MC335277?MCLinkSource=MajorUpdate__;Iw!!DfHvcUuWuuyr!59KccvthRTpMtDxYKoVlj7vkYuvNxlupWAfAsARsKkR39KAwkJ6N8zIeBZK6WNPk$",
         "https://urldefense.com/v3/__https://docs.microsoft.com/azure/active-directory/users-groups-roles/linkedin-integration__;!!DfHvcUuWuuyr!59KccvthRTpMtDxYKoVlj7vkYuvNxlupWAfAsARsKkR39KAwkJ6N8zIeBU7Yqr-6$",
         "https://docs.microsoft.com/azure/active-directory/users-groups-roles/linkedin-integration",
         "https://go.microsoft.com/fwlink/?LinkId=521839",
         "https://admin.microsoft.com/AdminPortal/home#/MessageCenter/:/messages/MC335277?MCLinkSource=MajorUpdate",
         "https://urldefense.com/v3/__https://go.microsoft.com/fwlink/?LinkId=521839__;!!DfHvcUuWuuyr!59KccvthRTpMtDxYKoVlj7vkYuvNxlupWAfAsARsKkR39KAwkJ6N8zIeBQQbTKa-$",
         "https://urldefense.com/v3/__https://docs.microsoft.com/azure/active-directory/enterprise-users/linkedin-integration__;!!DfHvcUuWuuyr!59KccvthRTpMtDxYKoVlj7vkYuvNxlupWAfAsARsKkR39KAwkJ6N8zIeBdadrnub$",
         "https://urldefense.com/v3/__https://docs.microsoft.com/en-us/microsoft-365/admin/manage/language-translation-for-message-center-posts?view=o365-worldwide__;!!DfHvcUuWuuyr!59KccvthRTpMtDxYKoVlj7vkYuvNxlupWAfAsARsKkR39KAwkJ6N8zIeBcMEwkML$",
         "http://www.w3.org/1999/xhtml",
         "https://docs.microsoft.com/en-us/microsoft-365/admin/manage/language-translation-for-message-center-posts?view=o365-worldwide",
         "https://img-prod-cms-rt-microsoft-com.akamaized.net/cms/api/am/imageFileData/RWWrZs?ver=3d7d",
         "https://admin.microsoft.com/adminportal/home#/MessageCenter/:/mcpreferences",
         "https://urldefense.com/v3/__https://www.microsoft.com/microsoft-365/roadmap?filters=\u0026searchterms=89132__;!!DfHvcUuWuuyr!59KccvthRTpMtDxYKoVlj7vkYuvNxlupWAfAsARsKkR39KAwkJ6N8zIeBTcv1yFl$"
      ]
   },
   "id": 100,
   "incident_field_values": [
      {
         "name": "Classification",
         "value": "Reported Abuse"
      },
      {
         "name": "Attack Vector",
         "value": "Email"
      },
      {
         "name": "Phantom Quarantine",
         "value": null
      },
      {
         "name": "CLEAR Analysis Complete",
         "value": null
      },
      {
         "name": "AlertSource",
         "value": null
      },
      {
         "name": "Abuse Disposition",
         "value": "Unknown"
      },
      {
         "name": "Sub Disposition",
         "value": null
      },
      {
         "name": "Severity",
         "value": "Informational"
      }
   ],
   "pending_quarantines": 0,
   "quarantine_results": [],
   "score": 1000,
   "state": "Closed",
   "successful_quarantines": 0,
   "summary": "",
   "team": "Unassigned",
   "updated_at": "2022-05-06T06:14:48Z",
   "users": []
}
```

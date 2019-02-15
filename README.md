<configuration>
<params>
<param name="CreditReportService" description="Отчет о кредитной истории">
<type>setting</type>
<enabled>true</enabled>
<creditReportServiceTutorialEnabled>true</creditReportServiceTutorialEnabled>
<creditReportServiceGetpdfEnabled>true</creditReportServiceGetpdfEnabled>
</param>
<param name="PriorityCardP2PServiceWrongCardsExclude" description="Исключение карт с истекшим сроком действия из списка карт, которые можно выбрать приоритетной">
<type>setting</type>
<enabled>false</enabled>
</param>
<param name="TransfersPostcard" description="Прикрепление открытки в p2p переводах">
<type>setting</type>
<enabled>true</enabled>
</param>
<param name="Loyalty" description="Программа лояльности «Спасибо от Сбербанка»">
<type>list</type>
<enabled>true</enabled>
<nodes>
<node id="mobile.sberbank.ru" description="Стенд ПСИ">
<bonusBalance>true</bonusBalance>
<dashboard>true</dashboard>
<offers>true</offers>
<charityPLSpasibo>true</charityPLSpasibo>
<distanceToNearestSalesPoint>true</distanceToNearestSalesPoint>
<ClientPrivilegeLevel>true</ClientPrivilegeLevel>
</node>
<node id="ift-node1.testonline.sberbank.ru" description="Стенд ИФТ блок 1">
<bonusBalance>true</bonusBalance>
<dashboard>true</dashboard>
<offers>true</offers>
<charityPLSpasibo>true</charityPLSpasibo>
<distanceToNearestSalesPoint>true</distanceToNearestSalesPoint>
<ClientPrivilegeLevel>true</ClientPrivilegeLevel>
</node>
<node id="ift-node2.testonline.sberbank.ru" description="Стенд ИФТ блок 2">
<bonusBalance>true</bonusBalance>
<dashboard>true</dashboard>
<offers>true</offers>
<charityPLSpasibo>true</charityPLSpasibo>
<distanceToNearestSalesPoint>true</distanceToNearestSalesPoint>
<ClientPrivilegeLevel>true</ClientPrivilegeLevel>
</node>
<node id="ift-node1-mp.testonline.sberbank.ru" description="Стенд ИФТ блок 1 (мобильный)">
<bonusBalance>true</bonusBalance>
<dashboard>true</dashboard>
<offers>true</offers>
<charityPLSpasibo>true</charityPLSpasibo>
<distanceToNearestSalesPoint>true</distanceToNearestSalesPoint>
<ClientPrivilegeLevel>true</ClientPrivilegeLevel>
</node>
<node id="ift-node2-mp.testonline.sberbank.ru" description="Стенд ИФТ блок 2 (мобильный)">
<bonusBalance>true</bonusBalance>
<dashboard>true</dashboard>
<offers>true</offers>
<charityPLSpasibo>true</charityPLSpasibo>
<distanceToNearestSalesPoint>true</distanceToNearestSalesPoint>
<ClientPrivilegeLevel>true</ClientPrivilegeLevel>
</node>
<node id="ift-node3-mp.testonline.sberbank.ru" description="Стенд ИФТ блок 3 (мобильный)">
<bonusBalance>true</bonusBalance>
<dashboard>true</dashboard>
<offers>true</offers>
<charityPLSpasibo>true</charityPLSpasibo>
<distanceToNearestSalesPoint>true</distanceToNearestSalesPoint>
<ClientPrivilegeLevel>true</ClientPrivilegeLevel>
</node>
<node id="ift-node4-mp.testonline.sberbank.ru" description="Стенд ИФТ блок 4 (мобильный)">
<bonusBalance>true</bonusBalance>
<dashboard>true</dashboard>
<offers>true</offers>
<charityPLSpasibo>true</charityPLSpasibo>
<distanceToNearestSalesPoint>true</distanceToNearestSalesPoint>
<ClientPrivilegeLevel>true</ClientPrivilegeLevel>
</node>
<node id="ift-node5-mp.testonline.sberbank.ru" description="Стенд ИФТ блок 5 (мобильный)">
<bonusBalance>true</bonusBalance>
<dashboard>true</dashboard>
<offers>true</offers>
<charityPLSpasibo>true</charityPLSpasibo>
<distanceToNearestSalesPoint>true</distanceToNearestSalesPoint>
<ClientPrivilegeLevel>true</ClientPrivilegeLevel>
</node>
<node id="node0.online.sberbank.ru">
<bonusBalance>true</bonusBalance>
<dashboard>true</dashboard>
<offers>true</offers>
<charityPLSpasibo>true</charityPLSpasibo>
<distanceToNearestSalesPoint>true</distanceToNearestSalesPoint>
<ClientPrivilegeLevel>true</ClientPrivilegeLevel>
</node>
<node id="node1.online.sberbank.ru">
<bonusBalance>true</bonusBalance>
<dashboard>true</dashboard>
<offers>true</offers>
<charityPLSpasibo>true</charityPLSpasibo>
<distanceToNearestSalesPoint>true</distanceToNearestSalesPoint>
<ClientPrivilegeLevel>true</ClientPrivilegeLevel>
</node>
<node id="node2.online.sberbank.ru">
<bonusBalance>true</bonusBalance>
<dashboard>true</dashboard>
<offers>true</offers>
<charityPLSpasibo>true</charityPLSpasibo>
<distanceToNearestSalesPoint>true</distanceToNearestSalesPoint>
<ClientPrivilegeLevel>true</ClientPrivilegeLevel>
</node>
<node id="node3.online.sberbank.ru">
<bonusBalance>true</bonusBalance>
<dashboard>true</dashboard>
<offers>true</offers>
<charityPLSpasibo>true</charityPLSpasibo>
<distanceToNearestSalesPoint>true</distanceToNearestSalesPoint>
<ClientPrivilegeLevel>true</ClientPrivilegeLevel>
</node>
<node id="node4.online.sberbank.ru">
<bonusBalance>true</bonusBalance>
<dashboard>true</dashboard>
<offers>true</offers>
<charityPLSpasibo>true</charityPLSpasibo>
<distanceToNearestSalesPoint>true</distanceToNearestSalesPoint>
<ClientPrivilegeLevel>true</ClientPrivilegeLevel>
</node>
<node id="greenfield1.online.sberbank.ru">
<bonusBalance>true</bonusBalance>
<dashboard>true</dashboard>
<offers>true</offers>
<charityPLSpasibo>true</charityPLSpasibo>
<distanceToNearestSalesPoint>true</distanceToNearestSalesPoint>
<ClientPrivilegeLevel>true</ClientPrivilegeLevel>
</node>
</nodes>
</param>
<param name="LoyaltyPreloginZone" description="Прелогин зона Спасибо">
<type>list</type>
<enabled>true</enabled>
</param>
<param name="Premier" description="Функционал Сбербанк Пресмьер">
<type>list</type>
<nodes>
<node id="mobile.sberbank.ru" description="Стенд ПСИ">
<distanceMarking>true</distanceMarking>
<appointmentListLoading>true</appointmentListLoading>
<appointmentCreation>true</appointmentCreation>
</node>
<node id="ift-node1.testonline.sberbank.ru" description="Стенд ИФТ блок 1">
<distanceMarking>true</distanceMarking>
<appointmentListLoading>true</appointmentListLoading>
<appointmentCreation>true</appointmentCreation>
</node>
<node id="ift-node2.testonline.sberbank.ru" description="Стенд ИФТ блок 2">
<distanceMarking>true</distanceMarking>
<appointmentListLoading>true</appointmentListLoading>
<appointmentCreation>true</appointmentCreation>
</node>
<node id="ift-node1-mp.testonline.sberbank.ru" description="Стенд ИФТ блок 1 (мобильный)">
<distanceMarking>true</distanceMarking>
<appointmentListLoading>true</appointmentListLoading>
<appointmentCreation>true</appointmentCreation>
</node>
<node id="ift-node2-mp.testonline.sberbank.ru" description="Стенд ИФТ блок 2 (мобильный)">
<distanceMarking>true</distanceMarking>
<appointmentListLoading>true</appointmentListLoading>
<appointmentCreation>true</appointmentCreation>
</node>
</nodes>
</param>
<param name="RecommendedDebt" description="Смарт Счета">
<type>service</type>
<enabled>true</enabled>
<nodes>
<node id="node0.online.sberbank.ru">
<enabled>false</enabled>
<paymentsServiceTutorial>false</paymentsServiceTutorial>
<debtServiceTutorial>false</debtServiceTutorial>
<paymentService>false</paymentService>
<paymentService_v96>false</paymentService_v96>
<debtService>false</debtService>
<debtRemoveService>false</debtRemoveService>
<debtRenameService>false</debtRenameService>
</node>
<node id="node1.online.sberbank.ru">
<enabled>false</enabled>
<paymentsServiceTutorial>false</paymentsServiceTutorial>
<debtServiceTutorial>false</debtServiceTutorial>
<paymentService>false</paymentService>
<paymentService_v96>false</paymentService_v96>
<debtService>false</debtService>
<debtRemoveService>false</debtRemoveService>
<debtRenameService>false</debtRenameService>
</node>
<node id="node2.online.sberbank.ru">
<enabled>false</enabled>
<paymentsServiceTutorial>false</paymentsServiceTutorial>
<debtServiceTutorial>false</debtServiceTutorial>
<paymentService>false</paymentService>
<paymentService_v96>false</paymentService_v96>
<debtService>false</debtService>
<debtRemoveService>false</debtRemoveService>
<debtRenameService>false</debtRenameService>
</node>
<node id="node3.online.sberbank.ru">
<enabled>false</enabled>
<paymentsServiceTutorial>false</paymentsServiceTutorial>
<debtServiceTutorial>false</debtServiceTutorial>
<paymentService>false</paymentService>
<paymentService_v96>false</paymentService_v96>
<debtService>false</debtService>
<debtRemoveService>false</debtRemoveService>
<debtRenameService>false</debtRenameService>
</node>
<node id="node4.online.sberbank.ru">
<enabled>false</enabled>
<paymentsServiceTutorial>false</paymentsServiceTutorial>
<debtServiceTutorial>false</debtServiceTutorial>
<paymentService>false</paymentService>
<paymentService_v96>false</paymentService_v96>
<debtService>false</debtService>
<debtRemoveService>false</debtRemoveService>
<debtRenameService>false</debtRenameService>
</node>
<node id="greenfield1.online.sberbank.ru">
<enabled>false</enabled>
<paymentsServiceTutorial>false</paymentsServiceTutorial>
<debtServiceTutorial>false</debtServiceTutorial>
<paymentService>false</paymentService>
<paymentService_v96>false</paymentService_v96>
<debtService>false</debtService>
<debtRemoveService>false</debtRemoveService>
<debtRenameService>false</debtRenameService>
</node>
<node id="greenfield2.online.sberbank.ru">
<enabled>false</enabled>
<paymentsServiceTutorial>false</paymentsServiceTutorial>
<debtServiceTutorial>false</debtServiceTutorial>
<paymentService>false</paymentService>
<paymentService_v96>false</paymentService_v96>
<debtService>false</debtService>
<debtRemoveService>false</debtRemoveService>
<debtRenameService>false</debtRenameService>
</node>
<node id="mobile.sberbank.ru">
<enabled>true</enabled>
<paymentsServiceTutorial>false</paymentsServiceTutorial>
<debtServiceTutorial>false</debtServiceTutorial>
<paymentService>false</paymentService>
<paymentService_v96>true</paymentService_v96>
<debtService>true</debtService>
<debtRemoveService>true</debtRemoveService>
<debtRenameService>true</debtRenameService>
</node>
<node id="ift-node1.testonline.sberbank.ru">
<enabled>true</enabled>
<paymentsServiceTutorial>false</paymentsServiceTutorial>
<debtServiceTutorial>false</debtServiceTutorial>
<paymentService>false</paymentService>
<paymentService_v96>true</paymentService_v96>
<debtService>true</debtService>
<debtRemoveService>true</debtRemoveService>
<debtRenameService>true</debtRenameService>
</node>
<node id="ift-node2.testonline.sberbank.ru">
<enabled>true</enabled>
<paymentsServiceTutorial>false</paymentsServiceTutorial>
<debtServiceTutorial>false</debtServiceTutorial>
<paymentService>false</paymentService>
<paymentService_v96>false</paymentService_v96>
<debtService>true</debtService>
<debtRemoveService>true</debtRemoveService>
<debtRenameService>false</debtRenameService>
</node>
<node id="ift-node3.testonline.sberbank.ru">
<enabled>true</enabled>
<paymentsServiceTutorial>false</paymentsServiceTutorial>
<debtServiceTutorial>false</debtServiceTutorial>
<paymentService>false</paymentService>
<paymentService_v96>true</paymentService_v96>
<debtService>true</debtService>
<debtRemoveService>true</debtRemoveService>
<debtRenameService>true</debtRenameService>
</node>
<node id="ift-node4.testonline.sberbank.ru">
<enabled>true</enabled>
<paymentsServiceTutorial>false</paymentsServiceTutorial>
<debtServiceTutorial>false</debtServiceTutorial>
<paymentService>false</paymentService>
<paymentService_v96>true</paymentService_v96>
<debtService>true</debtService>
<debtRemoveService>true</debtRemoveService>
<debtRenameService>true</debtRenameService>
</node>
<node id="ift-node5.testonline.sberbank.ru">
<enabled>true</enabled>
<paymentsServiceTutorial>false</paymentsServiceTutorial>
<debtServiceTutorial>false</debtServiceTutorial>
<paymentService>false</paymentService>
<paymentService_v96>true</paymentService_v96>
<debtService>true</debtService>
<debtRemoveService>true</debtRemoveService>
<debtRenameService>true</debtRenameService>
</node>
<node id="ift-node1-mp.testonline.sberbank.ru">
<enabled>true</enabled>
<paymentsServiceTutorial>false</paymentsServiceTutorial>
<debtServiceTutorial>false</debtServiceTutorial>
<paymentService>false</paymentService>
<paymentService_v96>true</paymentService_v96>
<debtService>true</debtService>
<debtRemoveService>true</debtRemoveService>
<debtRenameService>true</debtRenameService>
</node>
<node id="ift-node2-mp.testonline.sberbank.ru">
<enabled>true</enabled>
<paymentsServiceTutorial>false</paymentsServiceTutorial>
<debtServiceTutorial>false</debtServiceTutorial>
<paymentService>false</paymentService>
<paymentService_v96>true</paymentService_v96>
<debtService>true</debtService>
<debtRemoveService>true</debtRemoveService>
<debtRenameService>true</debtRenameService>
</node>
<node id="ift-node3-mp.testonline.sberbank.ru">
<enabled>true</enabled>
<paymentsServiceTutorial>false</paymentsServiceTutorial>
<debtServiceTutorial>false</debtServiceTutorial>
<paymentService>false</paymentService>
<paymentService_v96>true</paymentService_v96>
<debtService>true</debtService>
<debtRemoveService>true</debtRemoveService>
<debtRenameService>true</debtRenameService>
</node>
<node id="ift-node4-mp.testonline.sberbank.ru">
<enabled>true</enabled>
<paymentsServiceTutorial>false</paymentsServiceTutorial>
<debtServiceTutorial>false</debtServiceTutorial>
<paymentService>false</paymentService>
<paymentService_v96>true</paymentService_v96>
<debtService>true</debtService>
<debtRemoveService>true</debtRemoveService>
<debtRenameService>true</debtRenameService>
</node>
<node id="ift-node5-mp.testonline.sberbank.ru">
<enabled>true</enabled>
<paymentsServiceTutorial>false</paymentsServiceTutorial>
<debtServiceTutorial>false</debtServiceTutorial>
<paymentService>false</paymentService>
<paymentService_v96>true</paymentService_v96>
<debtService>true</debtService>
<debtRemoveService>true</debtRemoveService>
<debtRenameService>true</debtRenameService>
</node>
<node id="psinode2.testonline.sberbank.ru">
<enabled>true</enabled>
<paymentsServiceTutorial>false</paymentsServiceTutorial>
<debtServiceTutorial>false</debtServiceTutorial>
<paymentService>false</paymentService>
<paymentService_v96>true</paymentService_v96>
<debtService>true</debtService>
<debtRemoveService>true</debtRemoveService>
<debtRenameService>true</debtRenameService>
</node>
<node id="psinode1.testonline.sberbank.ru">
<enabled>true</enabled>
<paymentsServiceTutorial>false</paymentsServiceTutorial>
<debtServiceTutorial>false</debtServiceTutorial>
<paymentService>false</paymentService>
<paymentService_v96>true</paymentService_v96>
<debtService>true</debtService>
<debtRemoveService>true</debtRemoveService>
<debtRenameService>true</debtRenameService>
</node>
<node id="194.186.207.23">
<enabled>false</enabled>
<paymentsServiceTutorial>false</paymentsServiceTutorial>
<debtServiceTutorial>false</debtServiceTutorial>
<paymentService>false</paymentService>
<paymentService_v96>false</paymentService_v96>
<debtService>false</debtService>
<debtRemoveService>false</debtRemoveService>
<debtRenameService>false</debtRenameService>
</node>
</nodes>
</param>
<param name="DebitCardAppMP" description="Заказ дебетовых карт">
<type>service</type>
<enabled>true</enabled>
<enabled_8_7>true</enabled_8_7>
<digitalcardshow>true</digitalcardshow>
<ikaotransliteration>false</ikaotransliteration>
<apiv2>true</apiv2>
<api_urls>
<api_url name="searchBranches_v1" url="/card/v1/mobile/rest/searchBranches"/>
<api_url name="searchBranches_v2" url="/card/v2/mobile/rest/searchBranches"/>
<api_url name="init_v1" url="/card/v1/mobile/rest/init"/>
<api_url name="init_v2" url="/card/v2/mobile/rest/init"/>
<api_url name="create_v1" url="/card/v1/mobile/rest/create"/>
<api_url name="create_v2" url="/card/v2/mobile/rest/create"/>
<api_url name="send_v1" url="/card/v1/mobile/rest/send"/>
<api_url name="send_v2" url="/card/v2/mobile/rest/send"/>
<api_url name="operationHistory_v1" url="/card/v1/mobile/rest/OperationHistory"/>
<api_url name="operationHistory_v2" url="/card/v2/mobile/rest/OperationHistory"/>
<api_url name="countries_v1" url="/card/v1/mobile/rest/countries"/>
<api_url name="countries_v2" url="/card/v2/mobile/rest/countries"/>
</api_urls>
<nodes>
<node id="node0.online.sberbank.ru">
<enabled>true</enabled>
<apiv2>false</apiv2>
<fatkashow>false</fatkashow>
<ufsbranches>true</ufsbranches>
<ufshistory>true</ufshistory>
<digitalcardshow>false</digitalcardshow>
<ikaotransliteration>false</ikaotransliteration>
</node>
<node id="node1.online.sberbank.ru">
<enabled>true</enabled>
<apiv2>true</apiv2>
<fatkashow>false</fatkashow>
<ufsbranches>false</ufsbranches>
<ufshistory>true</ufshistory>
<digitalcardshow>false</digitalcardshow>
<ikaotransliteration>false</ikaotransliteration>
</node>
<node id="node2.online.sberbank.ru">
<enabled>true</enabled>
<apiv2>true</apiv2>
<fatkashow>false</fatkashow>
<ufsbranches>false</ufsbranches>
<ufshistory>true</ufshistory>
<digitalcardshow>false</digitalcardshow>
<ikaotransliteration>false</ikaotransliteration>
</node>
<node id="node3.online.sberbank.ru">
<enabled>true</enabled>
<apiv2>true</apiv2>
<fatkashow>false</fatkashow>
<ufsbranches>false</ufsbranches>
<ufshistory>true</ufshistory>
<digitalcardshow>false</digitalcardshow>
<ikaotransliteration>false</ikaotransliteration>
</node>
<node id="node4.online.sberbank.ru">
<enabled>true</enabled>
<apiv2>true</apiv2>
<fatkashow>false</fatkashow>
<ufsbranches>false</ufsbranches>
<ufshistory>true</ufshistory>
<digitalcardshow>false</digitalcardshow>
<ikaotransliteration>false</ikaotransliteration>
</node>
<node id="greenfield1.online.sberbank.ru">
<enabled>true</enabled>
<apiv2>true</apiv2>
<fatkashow>false</fatkashow>
<ufsbranches>true</ufsbranches>
<ufshistory>true</ufshistory>
<digitalcardshow>true</digitalcardshow>
<ikaotransliteration>false</ikaotransliteration>
</node>
<node id="greenfield2.online.sberbank.ru">
<enabled>true</enabled>
<apiv2>true</apiv2>
<fatkashow>false</fatkashow>
<ufsbranches>true</ufsbranches>
<ufshistory>true</ufshistory>
<digitalcardshow>true</digitalcardshow>
<ikaotransliteration>false</ikaotransliteration>
</node>
<node id="mobile.sberbank.ru">
<enabled>true</enabled>
<apiv2>true</apiv2>
<fatkashow>false</fatkashow>
<ufsbranches>true</ufsbranches>
<ufshistory>true</ufshistory>
<digitalcardshow>true</digitalcardshow>
<ikaotransliteration>false</ikaotransliteration>
</node>
<node id="ift-node1.testonline.sberbank.ru">
<enabled>true</enabled>
<apiv2>true</apiv2>
<fatkashow>false</fatkashow>
<ufsbranches>true</ufsbranches>
<ufshistory>true</ufshistory>
<digitalcardshow>true</digitalcardshow>
<ikaotransliteration>false</ikaotransliteration>
</node>
<node id="ift-node2.testonline.sberbank.ru">
<enabled>true</enabled>
<apiv2>true</apiv2>
<fatkashow>false</fatkashow>
<ufsbranches>true</ufsbranches>
<ufshistory>true</ufshistory>
<digitalcardshow>true</digitalcardshow>
<ikaotransliteration>false</ikaotransliteration>
</node>
<node id="ift-node1-mp.testonline.sberbank.ru">
<enabled>true</enabled>
<apiv2>true</apiv2>
<fatkashow>false</fatkashow>
<ufsbranches>true</ufsbranches>
<ufshistory>true</ufshistory>
<digitalcardshow>true</digitalcardshow>
<ikaotransliteration>false</ikaotransliteration>
</node>
<node id="ift-node2-mp.testonline.sberbank.ru">
<enabled>true</enabled>
<apiv2>true</apiv2>
<fatkashow>false</fatkashow>
<ufsbranches>true</ufsbranches>
<ufshistory>true</ufshistory>
<digitalcardshow>true</digitalcardshow>
<ikaotransliteration>false</ikaotransliteration>
</node>
<node id="ift-node5-mp.testonline.sberbank.ru">
<enabled>true</enabled>
<apiv2>true</apiv2>
<fatkashow>false</fatkashow>
<ufsbranches>true</ufsbranches>
<ufshistory>true</ufshistory>
<digitalcardshow>true</digitalcardshow>
<ikaotransliteration>false</ikaotransliteration>
</node>
<node id="psinode2.testonline.sberbank.ru">
<enabled>true</enabled>
<apiv2>true</apiv2>
<fatkashow>false</fatkashow>
<ufsbranches>true</ufsbranches>
<ufshistory>true</ufshistory>
<digitalcardshow>true</digitalcardshow>
<ikaotransliteration>false</ikaotransliteration>
</node>
<node id="psinode1.testonline.sberbank.ru">
<enabled>true</enabled>
<apiv2>true</apiv2>
<fatkashow>false</fatkashow>
<ufsbranches>true</ufsbranches>
<ufshistory>true</ufshistory>
<digitalcardshow>true</digitalcardshow>
<ikaotransliteration>false</ikaotransliteration>
</node>
<node id="194.186.207.23">
<enabled>true</enabled>
<apiv2>true</apiv2>
<fatkashow>false</fatkashow>
<ufsbranches>true</ufsbranches>
<ufshistory>true</ufshistory>
<digitalcardshow>true</digitalcardshow>
<ikaotransliteration>false</ikaotransliteration>
</node>
</nodes>
</param>
<param name="DigitalCardAppMP" description="Заказ цифровых карт">
<type>service</type>
<embossingtitle>Имя владельца</embossingtitle>
<embossingvalue>DIGITAL CARD</embossingvalue>
<embossingdescription>Это поле может пригодиться для оплаты в интернете</embossingdescription>
<enabled>true</enabled>
<tutor>true</tutor>
<showhints>true</showhints>
<classic-encryption>true</classic-encryption>
<nodes>
<node id="node0.online.sberbank.ru">
<enabled>true</enabled>
<fatkashow>false</fatkashow>
<getcvv>true</getcvv>
<ufshistory>true</ufshistory>
<blocknotification>true</blocknotification>
<embossingenabled>true</embossingenabled>
<showhints>true</showhints>
</node>
<node id="node1.online.sberbank.ru">
<enabled>true</enabled>
<fatkashow>false</fatkashow>
<getcvv>true</getcvv>
<ufshistory>true</ufshistory>
<blocknotification>true</blocknotification>
<embossingenabled>true</embossingenabled>
<showhints>true</showhints>
</node>
<node id="node2.online.sberbank.ru">
<enabled>true</enabled>
<fatkashow>false</fatkashow>
<getcvv>true</getcvv>
<ufshistory>true</ufshistory>
<blocknotification>true</blocknotification>
<embossingenabled>true</embossingenabled>
<showhints>true</showhints>
</node>
<node id="node3.online.sberbank.ru">
<enabled>true</enabled>
<fatkashow>false</fatkashow>
<getcvv>true</getcvv>
<ufshistory>true</ufshistory>
<blocknotification>true</blocknotification>
<embossingenabled>true</embossingenabled>
<showhints>true</showhints>
</node>
<node id="node4.online.sberbank.ru">
<enabled>true</enabled>
<fatkashow>false</fatkashow>
<getcvv>true</getcvv>
<ufshistory>true</ufshistory>
<blocknotification>true</blocknotification>
<embossingenabled>true</embossingenabled>
<showhints>true</showhints>
</node>
<node id="greenfield1.online.sberbank.ru">
<enabled>true</enabled>
<fatkashow>false</fatkashow>
<getcvv>true</getcvv>
<ufshistory>true</ufshistory>
<blocknotification>true</blocknotification>
<embossingenabled>true</embossingenabled>
<showhints>true</showhints>
<panrq>true</panrq>
<showhints>false</showhints>
</node>
<node id="greenfield2.online.sberbank.ru">
<enabled>true</enabled>
<fatkashow>false</fatkashow>
<getcvv>true</getcvv>
<ufshistory>true</ufshistory>
<blocknotification>true</blocknotification>
<embossingenabled>true</embossingenabled>
<showhints>true</showhints>
<panrq>true</panrq>
<showhints>false</showhints>
</node>
<node id="mobile.sberbank.ru">
<enabled>true</enabled>
<fatkashow>false</fatkashow>
<getcvv>true</getcvv>
<ufshistory>true</ufshistory>
<blocknotification>true</blocknotification>
<embossingenabled>true</embossingenabled>
<panmask>true</panmask>
<panrq>true</panrq>
<showhints>true</showhints>
<tutor>true</tutor>
</node>
<node id="ift-node1-mp.testonline.sberbank.ru">
<enabled>true</enabled>
<fatkashow>false</fatkashow>
<getcvv>true</getcvv>
<ufshistory>true</ufshistory>
<blocknotification>true</blocknotification>
<embossingenabled>true</embossingenabled>
<panmask>true</panmask>
<panrq>true</panrq>
<classic-encryption>true</classic-encryption>
<showhints>true</showhints>
<tutor>true</tutor>
</node>
<node id="ift-node2-mp.testonline.sberbank.ru">
<enabled>true</enabled>
<fatkashow>false</fatkashow>
<getcvv>true</getcvv>
<ufshistory>true</ufshistory>
<blocknotification>true</blocknotification>
<embossingenabled>true</embossingenabled>
<panmask>true</panmask>
<panrq>true</panrq>
<showhints>true</showhints>
<tutor>true</tutor>
</node>
<node id="ift-node5-mp.testonline.sberbank.ru">
<enabled>true</enabled>
<fatkashow>false</fatkashow>
<getcvv>true</getcvv>
<ufshistory>true</ufshistory>
<blocknotification>true</blocknotification>
<embossingenabled>true</embossingenabled>
<panmask>true</panmask>
<panrq>true</panrq>
<showhints>true</showhints>
<tutor>true</tutor>
</node>
</nodes>
</param>
<param name="CardPANRequest" description="Определение типов карт для которых доступен запрос полного номера карты">
<type>service</type>
<CardPANRqList>
<CardPANRq id="Visa Digital"/>
<CardPANRq id="Visa Classic"/>
<CardPANRq id="Visa Platinum"/>
<CardPANRq id="Visa Gold"/>
<CardPANRq id="MasterCard Mass"/>
<CardPANRq id="MIR"/>
<CardPANRq id="MIR Gold"/>
</CardPANRqList>
</param>
<param name="CardCVVSMS" description="Определение типов карт для которых доступен запрос CVC2/CVV2">
<type>service</type>
<cardCvvList>
<cardCvv id="Visa Digital"/>
<cardCvv id="Visa Classic"/>
<cardCvv id="Visa Platinum"/>
<cardCvv id="Visa Gold"/>
<cardCvv id="MasterCard Mass"/>
</cardCvvList>
</param>
<param name="SetPinForCard" description="Установка/смена ПИН-кода карты">
<enabled>true</enabled>
<warningEnabled>true</warningEnabled>
<showTutorial>false</showTutorial>
<demoEnabled>true</demoEnabled>
</param>
<param name="CardCVV" description="Определение типов карт для запроса CVV">
<type>list</type>
<enabled>true</enabled>
<key>name</key>
<cardCvvList>
<cardCvv id="Visa Classic"/>
<cardCvv id="MasterCard Mass"/>
<cardCvv id="Visa Digital"/>
<cardCvv id="Visa Platinum"/>
<cardCvv id="MasterCard Platinum"/>
<cardCvv id="Visa Virtual"/>
<cardCvv id="MIR"/>
<cardCvv id="MIR Gold"/>
</cardCvvList>
</param>
<param name="BlockingNotification" description="Карты с выводом нотификации при блокировке">
<type>service</type>
<cardBlockList>
<cardBlock id="Visa Classic"/>
<cardBlock id="MasterCard Mass"/>
<cardBlock id="Visa Digital"/>
</cardBlockList>
<notification>
<title>Перевести остаток средств перед блокировкой?</title>
<description>
Рекомендуем перед блокировкой карты перевести остаток средств на другую карту или счет. После блокировки карты получить денежные средства можно будет только в офисе банка при предъявлении документа, удостоверяющего личность
</description>
<buttontextcontinue>Продолжить</buttontextcontinue>
<buttontexttransfer>Перевести</buttontexttransfer>
</notification>
<reasonList>
<reason id="other"/>
</reasonList>
</param>
<param name="DebitCardBlockingNotification" description="Дебетовые карты с выводом нотификации при блокировке">
<type>service</type>
<enabled>true</enabled>
<cardBlockList>
<cardBlock id="Visa Classic"/>
<cardBlock id="MasterCard Mass"/>
<cardBlock id="Visa Digital"/>
</cardBlockList>
<notification>
<title>Перевести остаток средств перед блокировкой?</title>
<description>
Рекомендуем перед блокировкой карты перевести остаток средств на другую карту или счет. После блокировки карты получить денежные средства можно будет только в офисе банка при предъявлении документа, удостоверяющего личность
</description>
<buttontextcontinue>Продолжить</buttontextcontinue>
<buttontexttransfer>Перевести</buttontexttransfer>
</notification>
</param>
<param name="CardPANRq" description="Определение типов карт для запроса PAN-номера карты">
<type>list</type>
<enabled>true</enabled>
<key>name</key>
<CardPANRqList>
<CardPANRq id="Visa Classic"/>
<CardPANRq id="MasterCard Mass"/>
<CardPANRq id="Visa Digital"/>
<CardPANRq id="Visa Platinum"/>
<CardPANRq id="MasterCard Platinum"/>
<CardPANRq id="Visa Virtual"/>
</CardPANRqList>
</param>
<param name="CardPANMask" description="Определение типов карт для маскирования PAN-номера карты">
<type>list</type>
<enabled>true</enabled>
<CardPANMaskList>
<CardPANMask id="Visa Gold"/>
<CardPANMask id="Visa Classic"/>
<CardPANMask id="Visa Virtual"/>
<CardPANMask id="Visa Digital"/>
<CardPANMask id="Mastercard Virtual"/>
</CardPANMaskList>
</param>
<param name="pin_number" description="">
<type>setting</type>
<enabled>true</enabled>
<number>320</number>
</param>
<param name="alf" description="">
<type>setting</type>
<enabled>true</enabled>
</param>
<param name="uak" description="">
<type>setting</type>
<enabled>true</enabled>
<syncContacts>true</syncContacts>
</param>
<param name="avatar" description="">
<type>setting</type>
<enabled>true</enabled>
</param>
<param name="rating" description="">
<type>setting</type>
<enabled>true</enabled>
</param>
<param name="standin" description="">
<type>setting</type>
<enabled>true</enabled>
<host>node0.online.sberbank.ru</host>
</param>
<param name="gamification" description="">
<type>setting</type>
<enabled>false</enabled>
</param>
<param name="itunes_cards" description="">
<type>service</type>
<enabled>true</enabled>
</param>
<param name="aeroexpress" description="">
<type>service</type>
<enabled>true</enabled>
</param>
<param name="statement" description="Выписка по истории операций">
<type>list</type>
<enabled>true</enabled>
<nodes>
<node id="node0.online.sberbank.ru">
<cardStatementOperations>false</cardStatementOperations>
<StatementOperationsLimit>1000</StatementOperationsLimit>
<cardStatementTutorial>true</cardStatementTutorial>
<StatementPagination>true</StatementPagination>
<StatementPaginationSize>200</StatementPaginationSize>
<StatementPaginationLimit>30</StatementPaginationLimit>
</node>
<node id="node1.online.sberbank.ru">
<cardStatementOperations>false</cardStatementOperations>
<StatementOperationsLimit>1000</StatementOperationsLimit>
<cardStatementTutorial>true</cardStatementTutorial>
<StatementPagination>true</StatementPagination>
<StatementPaginationSize>200</StatementPaginationSize>
<StatementPaginationLimit>30</StatementPaginationLimit>
</node>
<node id="node2.online.sberbank.ru">
<cardStatementOperations>false</cardStatementOperations>
<StatementOperationsLimit>1000</StatementOperationsLimit>
<cardStatementTutorial>true</cardStatementTutorial>
<StatementPagination>true</StatementPagination>
<StatementPaginationSize>200</StatementPaginationSize>
<StatementPaginationLimit>30</StatementPaginationLimit>
</node>
<node id="node3.online.sberbank.ru">
<cardStatementOperations>false</cardStatementOperations>
<StatementOperationsLimit>1000</StatementOperationsLimit>
<cardStatementTutorial>true</cardStatementTutorial>
<StatementPagination>true</StatementPagination>
<StatementPaginationSize>200</StatementPaginationSize>
<StatementPaginationLimit>30</StatementPaginationLimit>
</node>
<node id="greenfield1.online.sberbank.ru">
<cardStatementOperations>true</cardStatementOperations>
<StatementOperationsLimit>1000</StatementOperationsLimit>
<cardStatementTutorial>true</cardStatementTutorial>
<StatementPagination>true</StatementPagination>
<StatementPaginationSize>200</StatementPaginationSize>
<StatementPaginationLimit>30</StatementPaginationLimit>
</node>
<node id="mobile.sberbank.ru">
<cardStatementOperations>true</cardStatementOperations>
<StatementOperationsLimit>1000</StatementOperationsLimit>
<cardStatementTutorial>true</cardStatementTutorial>
<StatementPagination>true</StatementPagination>
<StatementPaginationSize>200</StatementPaginationSize>
<StatementPaginationLimit>30</StatementPaginationLimit>
</node>
<node id="ift-node1-mp.testonline.sberbank.ru">
<cardStatementOperations>true</cardStatementOperations>
<StatementOperationsLimit>1000</StatementOperationsLimit>
<cardStatementTutorial>true</cardStatementTutorial>
<StatementPagination>true</StatementPagination>
<StatementPaginationSize>200</StatementPaginationSize>
<StatementPaginationLimit>30</StatementPaginationLimit>
</node>
<node id="ift-node2-mp.testonline.sberbank.ru">
<cardStatementOperations>true</cardStatementOperations>
<StatementOperationsLimit>1000</StatementOperationsLimit>
<cardStatementTutorial>true</cardStatementTutorial>
<StatementPagination>true</StatementPagination>
<StatementPaginationSize>200</StatementPaginationSize>
<StatementPaginationLimit>30</StatementPaginationLimit>
</node>
</nodes>
</param>
<param name="VMT" description="VISA MoneyTransfer">
<type>limit</type>
<enabled>true</enabled>
<minamount>1</minamount>
<maxamount>30000</maxamount>
<cumulative>30000</cumulative>
<currency>RUB</currency>
</param>
<param name="MCMS" description="MasterCard MoneySend">
<type>limit</type>
<enabled>true</enabled>
<minamount>1</minamount>
<maxamount>30000</maxamount>
<cumulative>150000</cumulative>
<currency>RUB</currency>
</param>
<param name="persInformation" description="Personal information">
<type>setting</type>
<enabled>false</enabled>
</param>
<param name="moneybox" description="">
<type>setting</type>
<enabled>true</enabled>
</param>
<param name="RurPaymentAddressInnExclude" description="Исключение Адреса и ИНН из перевода Клиенту">
<type>setting</type>
<enabled>true</enabled>
</param>
<param name="tarifPlanParams" description="">
<type>list</type>
<enabled>true</enabled>
<tarifPlans>
<tarifPlan id="0">
<phoneNumbers>
<phoneNumber cntr="ru" prior="1" addInfo="По России бесплатно (МТС, Билайн, Мегафон, Tele2, Yota, Мотив)" pin="320">900</phoneNumber>
<phoneNumber cntr="other" prior="2" addInfo="Из-за границы по тарифу оператора" pin="320">+7(495) 500-55-50</phoneNumber>
</phoneNumbers>
</tarifPlan>
<tarifPlan id="1">
<phoneNumbers>
<phoneNumber cntr="ru" prior="1" addInfo="По России бесплатно" pin="0">8-800-555-02-55</phoneNumber>
<phoneNumber cntr="other" prior="2" addInfo="Из-за границы по тарифу оператора" pin="0">+7(495) 669-06-38</phoneNumber>
</phoneNumbers>
</tarifPlan>
<tarifPlan id="2">
<phoneNumbers>
<phoneNumber cntr="ru" prior="1" addInfo="По России бесплатно (МТС, Билайн, Мегафон, Tele2, Yota, Мотив)" pin="320">900</phoneNumber>
<phoneNumber cntr="other" prior="2" addInfo="Из-за границы по тарифу оператора" pin="320">+7(495) 500-55-50</phoneNumber>
</phoneNumbers>
</tarifPlan>
<tarifPlan id="3">
<phoneNumbers>
<phoneNumber cntr="ru" prior="1" addInfo="По России бесплатно" pin="0">8-800-333-22-33</phoneNumber>
<phoneNumber cntr="other" prior="2" addInfo="Из-за границы по тарифу оператора" pin="0">+7(495) 544-45-40</phoneNumber>
</phoneNumbers>
</tarifPlan>
</tarifPlans>
</param>
<param name="HiddenStrings" description="Скрываемые сообщения">
<type>strings</type>
<strings>
<string>Регион сохранен</string>
<string>
Обратите внимание: последний раз Вы совершали данный платеж
</string>
<string>Обратите внимание! Не совпадает ФИО получателя.</string>
<string>
вы можете выполнить операцию без подтверждения в контактном центре
</string>
<string>Операция превысила суточный лимит.</string>
<string>
За выполнение данной операции комиссия не взимается
</string>
<string>
Обратите внимание! Вы можете выполнить операцию без подтверждения
</string>
<string>
Не удается получить карту перевода по указанному номеру телефона
</string>
<string>
Счет списания и счет зачисления должны быть различны
</string>
<string>
Операцию возможно выполнить только на вклад открытый в
</string>
<string>Ваш платеж успешно отправлен в банк на обработку!</string>
<string>
Операция успешно исполнена. Спасибо, что Вы воспользовались «Сбербанк Онлайн»!
</string>
<string>
Ваша заявка успешно отправлена в банк! Спасибо, что воспользовались системой "Сбербанк ОнЛайн"!
</string>
<string>АБС не доступна. Получение информации не возможно.</string>
<string>Информация из АБС временно недоступна.</string>
<string>По некоторым Вашим картам информация недоступна.</string>
<string>
За выполнение данной операции комиссия не взимается.
</string>
<string>
За данную операцию может взиматься комиссия в соответствии с тарифами банка. Сумму комиссии Вы можете посмотреть на сайте банка.
</string>
<string>В данный момент внешняя система неактивна.</string>
<string>Неверная авторизация. Неактивный mGUID.</string>
<string>
Ваша заявка успешно отправлена в банк! После исполнения заявки Вы увидите созданный автоплатеж, выбрав пункт «Управление автоплатежами» в разделе «Мои автоплатежи» личного меню. Спасибо, что воспользовались системой «Сбербанк Онлайн»!
</string>
<string>за данную операцию может взиматься комиссия</string>
<string>
Значение данного поля изменилось. При необходимости Вы можете его отредактировать
</string>
<string>
Платеж успешно отправлен в банк. Спасибо, что воспользовались «Сбербанк Онлайн»!
</string>
<string>
Обратите внимание! Вы не можете совершить операцию на сумму больше
</string>
<string>
Обратите внимание! Доступный лимит для совершения операции составляет
</string>
<string>Доступ к операции запрещен!</string>
<string>Изменение данных невозможно в данный момент</string>
</strings>
</param>
<param name="ReplaceableStrings" description="Заменяемые сообщения">
<type>strings</type>
<strings>
<string>
<old>
Операция превышает суточный лимит. Вы можете уменьшить сумму или для исполнения операции Вам потребуется подтвердить ее через Контактный центр банка.
</old>
<new>
Вы превысили лимит по текущей операции. Данный лимит действует в течение 24 часов. Вы можете уменьшить сумму или для исполнения операции Вам потребуется подтвердить ее через Контактный центр банка.
</new>
</string>
<string>
<old>
При выполнении этой операции Вы превысите суточный лимит для совершения переводов и оплаты услуг. Данная операция будет исполнена банком только после того, как Вы подтвердите ее через Контактный центр банка по телефонам +7 (495) 500 5550, 8 (800) 555 5550.
</old>
<new>
При выполнении этой операции вы превысите лимит на совершение переводов и оплаты услуг. Данный лимит действует в течение 24 часов. Вы можете уменьшить сумму или для исполнения операции Вам потребуется подтвердить ее через Контактный центр банка.
</new>
</string>
<string>
<old>
Вы превысили лимит по количеству операций перевода средств, выполняемых в течение суток. Операцию необходимо подтвердить в Контактном центре банка, позвонив по телефонам 8 (800) 555 5550, +7 (495) 500 5550.
</old>
<new>
Вы превысили лимит по количеству переводов, выполняемых в течение 24 часов. Операцию необходимо подтвердить в Контактном центре банка, позвонив по телефонам 8 (800) 555 5550, +7 (495) 500 5550.
</new>
</string>
<string>
<old>
Вы превысили лимит по количеству операций перевода средств, выполняемых в течение суток. Пожалуйста, повторите операцию позже.
</old>
<new>
Вы превысили лимит по количеству переводов, выполняемых в течение 24 часов. Пожалуйста, повторите операцию позже.
</new>
</string>
<string>
<old>
Вы превысили лимит на сумму операций перевода средств, выполняемых в течение суток. Операцию необходимо подтвердить в Контактном центре банка, позвонив по телефонам 8 (800) 555 5550, +7 (495) 500 5550.
</old>
<new>
Вы превысили лимит на сумму операций перевода средств, выполняемых в течение 24 часов. Операцию необходимо подтвердить в Контактном центре банка, позвонив по телефонам 8 (800) 555 5550, +7 (495) 500 5550.
</new>
</string>
<string>
<old>
Вы превысили суточный лимит денежных средств по операциям. Пожалуйста повторите попытку позже.
</old>
<new>
Вы превысили лимит по сумме переведенных средств. Данный лимит действует в течение 24 часов. Пожалуйста повторите попытку позже.
</new>
</string>
<string>
<old>
Вы превысили лимит на сумму перевода средств, выполняемых в течение суток.
</old>
<new>
Вы превысили лимит на сумму перевода средств. Данный лимит действует в течение 24 часов.
</new>
</string>
<string>
<old>
Регистрация перевода не возможна, у вас уже имеются зарегистрированные не выплаченные переводы
</old>
<new>
Чтобы сделать новый заказ, снимите деньги по активному коду в банкомате или отмените заказ в истории операций. Также, можно сделать заказ по другой карте.
</new>
</string>
<string>
<old>Ваш логин заблокирован. Повторите попытку позже.</old>
<new>
Вход в Сбербанк Онлайн заблокирован. Если вы забыли пароль, смените пользователя для повторной регистрации.
</new>
</string>
<string>
<old>Неверный логин или пароль!</old>
<new>
Вы ввели неверный пароль. У вас осталось 2 попытки. Если вы забыли пароль, смените пользователя для повторной регистрации.
</new>
</string>
<string>
<old>
Неверный логин или пароль. Следующая неверная попытка заблокирует вход в Сбербанк Онлайн на 05 мин
</old>
<new>
Вы ввели неверный пароль. Следующая неверная попытка заблокирует вход на 05 мин. Если вы забыли пароль, смените пользователя для повторной регистрации.
</new>
</string>
<string>
<old>
Вы ввели неправильный идентификатор или пароль из SMS. Пожалуйста, попробуйте снова.
</old>
<new>
Вы ввели неправильный идентификатор или код из СМС. Пожалуйста, попробуйте снова.
</new>
</string>
<string>
<old>
Вы превысили количество попыток ввода пароля для подтверждения операции. Пожалуйста, создайте новую заявку на регистрацию приложения.
</old>
<new>
Вы превысили количество попыток ввода кода для подтверждения операции. Пожалуйста, создайте новую заявку на регистрацию приложения.
</new>
</string>
</strings>
</param>
<param name="Manual" description="Руководство пользователя">
<type>link</type>
<link>
http://sberbank.ru/common/img/uploaded/files/pdf/Rukovodstvo_polzovatelya_iPhone.pdf
</link>
</param>
<param name="hide_category" description="">
<type>list</type>
<enabled>true</enabled>
<categories block="mobile.sberbank.ru">
<category>958</category>
<category>960</category>
<category>964</category>
</categories>
</param>
<param name="craudgifting" description="switch for craudgifting">
<type>setting</type>
<languages localeId="ru" enabled="true"/>
<languages localeId="en" enabled="false"/>
<receivers>15</receivers>
</param>
<param name="hide_receiver" description="Скрываемые ПУ по расч.счету">
<type>list</type>
<receiver>
<receiverAccount>40703810838000001730</receiverAccount>
<receiverAccount>40703810000020105994</receiverAccount>
<receiverAccount>40703810340350104626</receiverAccount>
<receiverAccount>40703810400020008374</receiverAccount>
<receiverAccount>40703810838060051270</receiverAccount>
<receiverAccount>40703810501200000086</receiverAccount>
<receiverAccount>40703810338040005076</receiverAccount>
<receiverAccount>40703810300001400860</receiverAccount>
<receiverAccount>40703810700001449489</receiverAccount>
<receiverAccount>40703810697950000000</receiverAccount>
<receiverAccount>40703810838090000738</receiverAccount>
<receiverAccount>40703810287810000000</receiverAccount>
<receiverAccount>40703810238000000975</receiverAccount>
<receiverAccount>40703810300000000065</receiverAccount>
<receiverAccount>40703810300020106444</receiverAccount>
<receiverAccount>30233810800002100002</receiverAccount>
<receiverAccount>40703810400020008390</receiverAccount>
<receiverAccount>40702810700020001166</receiverAccount>
<receiverAccount>40703810300020000003</receiverAccount>
<receiverAccount>40703810638260001712</receiverAccount>
<receiverAccount>40703810538000003135</receiverAccount>
<receiverAccount>40703810038000002584</receiverAccount>
<receiverAccount>40703810238000002575</receiverAccount>
<receiverAccount>40703810838040005110</receiverAccount>
<receiverAccount>40703810038120028888</receiverAccount>
<receiverAccount>40703810742050001889</receiverAccount>
<receiverAccount>40703810700000000261</receiverAccount>
<receiverAccount>40703810938060146056</receiverAccount>
<receiverAccount>40703810842000000028</receiverAccount>
<receiverAccount>40703810649770000700</receiverAccount>
<receiverAccount>40703810038060102864</receiverAccount>
<receiverAccount>40703810940020100046</receiverAccount>
<receiverAccount>40703810938040005463</receiverAccount>
<receiverAccount>40703810038040100912</receiverAccount>
<receiverAccount>40703810038290071192</receiverAccount>
<receiverAccount>40703810555040000121</receiverAccount>
<receiverAccount>40703810623000008598</receiverAccount>
<receiverAccount>40703810955090106280</receiverAccount>
<receiverAccount>40703810238110001411</receiverAccount>
<receiverAccount>40703810438180133973</receiverAccount>
<receiverAccount>40703810738110100676</receiverAccount>
<receiverAccount>40703810400000004744</receiverAccount>
<receiverAccount>40703810000000000072</receiverAccount>
<receiverAccount>40703810838110100628</receiverAccount>
<receiverAccount>40703810338260101174</receiverAccount>
<receiverAccount>40703810638040005611</receiverAccount>
<receiverAccount>40703810938050001321</receiverAccount>
<receiverAccount>40703810755100000010</receiverAccount>
<receiverAccount>40703810138170002547</receiverAccount>
<receiverAccount>40703810575000000009</receiverAccount>
<receiverAccount>40703810000000001150</receiverAccount>
<receiverAccount>40703810838000070062</receiverAccount>
<receiverAccount>40703810238000001301</receiverAccount>
<receiverAccount>40703810955040099198</receiverAccount>
<receiverAccount>40703810338320100413</receiverAccount>
<receiverAccount>40703810654400000542</receiverAccount>
<receiverAccount>40703810238290100685</receiverAccount>
<receiverAccount>40703810925000103890</receiverAccount>
<receiverAccount>40703810438000001266</receiverAccount>
<receiverAccount>40703810738000003116</receiverAccount>
<receiverAccount>40703810738260100759</receiverAccount>
<receiverAccount>40703810738170101233</receiverAccount>
<receiverAccount>40703810300030000036</receiverAccount>
<receiverAccount>40703810654060100293</receiverAccount>
<receiverAccount>40703810138000001155</receiverAccount>
<receiverAccount>40703810451150100097</receiverAccount>
<receiverAccount>40703810338110001751</receiverAccount>
<receiverAccount>40703810338000000891</receiverAccount>
<receiverAccount>40703810538070101258</receiverAccount>
<receiverAccount>40703810038260001820</receiverAccount>
<receiverAccount>40703810038170100772</receiverAccount>
<receiverAccount>40703810806000000112</receiverAccount>
<receiverAccount>40703810262000000624</receiverAccount>
<receiverAccount>40703810438180000307</receiverAccount>
<receiverAccount>40703810260300000879</receiverAccount>
<receiverAccount>40703810200000011387</receiverAccount>
<receiverAccount>40703810300020000003</receiverAccount>
<receiverAccount>40703810238000004230</receiverAccount>
</receiver>
</param>
<param name="showCorporateCard" description="Глобальный рубильник показа корпортаивных карт">
<type>setting</type>
<enabled>true</enabled>
</param>
<param name="charity_text" description="Текст при попытке оплаты благотворительного ПУ">
<type>strings</type>
<strings>
<string localeId="ru">
"К сожалению, оплата в пользу благотворительных организаций не может осуществляться в мобильном приложении для iOS по независящим от нас причинам. Вы можете совершить оплату через веб-версию Сбербанк Онлайн, любое отделение или банкомат Сбербанка."
</string>
</strings>
</param>
<param name="self_registration_translate" description="Замена строк при саморегистрации если локализация отлична от дефолтной">
<type>strings</type>
<strings>
<string>
<RU>попытки</RU>
<EN>attempts</EN>
</string>
<string>
<RU>
Пароль не должен повторять старые пароли за последние 3 месяца
</RU>
<EN>
The password must not repeat the old passwords in the last 3 months
</EN>
</string>
<string>
<RU>
Введенный идентификатор уже используется в системе. Введите другое значение
</RU>
<EN>
The entered ID is already in use in the system. Enter a different value
</EN>
</string>
</strings>
</param>
<param name="fundInfo" description="Получение информации о наличии у контактов МП про-версии">
<type>setting</type>
<enabled>true</enabled>
</param>
<param name="wrongpass" description="">
<type>list</type>
<enabled>true</enabled>
<attempts>
<attempt>
<localeId>ru</localeId>
<count>1</count>
<string>
Вы неверно ввели код 1 раз. Если вы 3 раза введете код неверно, вы будете заблокированы на 1 час
</string>
</attempt>
<attempt>
<localeId>ru</localeId>
<count>2</count>
<string>
Вы неверно ввели код 2 раза. У вас осталась 1 попытка. Если вы забыли код на вход, воспользуйтесь функцией «забыл код на вход».
</string>
</attempt>
</attempts>
</param>
<param name="marketplaceMainScreenOffer" description="">
<type>setting</type>
<enabled>true</enabled>
</param>
<param name="newmarketplace" description="Витрина 7.3.1">
<type>setting</type>
<enabled>true</enabled>
<recommendedEnabled>false</recommendedEnabled>
<urls>
<url name="marketplace_v1" url="http://sbertech.online/marketplace/config.ios.8.15.xml" version="9.1.0"/>
<url name="marketplace_v2" url="http://sbertech.online/marketplace/config.ios.9.2.xml" version="9.2.0"/>
<url name="marketplace_v2" url="http://sbertech.online/marketplace/config.ios.9.3.xml" version="9.3.0"/>
</urls>
<nodes>
<node id="node0.online.sberbank.ru">
<enabled_Marketplace_2_0>true</enabled_Marketplace_2_0>
<mainEntryEnabled>true</mainEntryEnabled>
<personalizationEnabled>true</personalizationEnabled>
</node>
<node id="node1.online.sberbank.ru">
<enabled_Marketplace_2_0>true</enabled_Marketplace_2_0>
<mainEntryEnabled>true</mainEntryEnabled>
<personalizationEnabled>true</personalizationEnabled>
</node>
<node id="node2.online.sberbank.ru">
<enabled_Marketplace_2_0>true</enabled_Marketplace_2_0>
<mainEntryEnabled>true</mainEntryEnabled>
<personalizationEnabled>true</personalizationEnabled>
</node>
<node id="node3.online.sberbank.ru">
<enabled_Marketplace_2_0>true</enabled_Marketplace_2_0>
<mainEntryEnabled>true</mainEntryEnabled>
<personalizationEnabled>true</personalizationEnabled>
</node>
<node id="node4.online.sberbank.ru">
<enabled_Marketplace_2_0>true</enabled_Marketplace_2_0>
<mainEntryEnabled>true</mainEntryEnabled>
<personalizationEnabled>true</personalizationEnabled>
</node>
<node id="greenfield1.online.sberbank.ru">
<enabled_Marketplace_2_0>true</enabled_Marketplace_2_0>
<mainEntryEnabled>true</mainEntryEnabled>
<personalizationEnabled>true</personalizationEnabled>
</node>
<node id="greenfield2.online.sberbank.ru">
<enabled_Marketplace_2_0>true</enabled_Marketplace_2_0>
<mainEntryEnabled>true</mainEntryEnabled>
<personalizationEnabled>true</personalizationEnabled>
</node>
<node id="194.186.207.23">
<enabled_Marketplace_2_0>true</enabled_Marketplace_2_0>
<mainEntryEnabled>true</mainEntryEnabled>
<personalizationEnabled>true</personalizationEnabled>
</node>
<node id="mobile.sberbank.ru">
<enabled_Marketplace_2_0>true</enabled_Marketplace_2_0>
<mainEntryEnabled>true</mainEntryEnabled>
<personalizationEnabled>true</personalizationEnabled>
</node>
<node id="ift-node1.testonline.sberbank.ru">
<enabled_Marketplace_2_0>true</enabled_Marketplace_2_0>
<mainEntryEnabled>false</mainEntryEnabled>
<personalizationEnabled>true</personalizationEnabled>
</node>
<node id="ift-node2.testonline.sberbank.ru">
<enabled_Marketplace_2_0>true</enabled_Marketplace_2_0>
<mainEntryEnabled>true</mainEntryEnabled>
<personalizationEnabled>true</personalizationEnabled>
</node>
<node id="ift-node0-mp.testonline.sberbank.ru">
<enabled_Marketplace_2_0>true</enabled_Marketplace_2_0>
<mainEntryEnabled>true</mainEntryEnabled>
<personalizationEnabled>true</personalizationEnabled>
</node>
<node id="ift-node1-mp.testonline.sberbank.ru">
<enabled_Marketplace_2_0>true</enabled_Marketplace_2_0>
<mainEntryEnabled>true</mainEntryEnabled>
<personalizationEnabled>true</personalizationEnabled>
</node>
<node id="ift-node2-mp.testonline.sberbank.ru">
<enabled_Marketplace_2_0>true</enabled_Marketplace_2_0>
<mainEntryEnabled>true</mainEntryEnabled>
<personalizationEnabled>true</personalizationEnabled>
</node>
<node id="ift-node5-mp.testonline.sberbank.ru">
<enabled_Marketplace_2_0>true</enabled_Marketplace_2_0>
<mainEntryEnabled>true</mainEntryEnabled>
<personalizationEnabled>true</personalizationEnabled>
</node>
<node id="psinode2.testonline.sberbank.ru">
<enabled_Marketplace_2_0>true</enabled_Marketplace_2_0>
<mainEntryEnabled>true</mainEntryEnabled>
<personalizationEnabled>true</personalizationEnabled>
</node>
<node id="psinode1.testonline.sberbank.ru">
<enabled_Marketplace_2_0>true</enabled_Marketplace_2_0>
<mainEntryEnabled>true</mainEntryEnabled>
<personalizationEnabled>true</personalizationEnabled>
</node>
</nodes>
</param>
<param name="marketplace_search_ignore" description="Не отображение в поиске определенных поставщиков услуг">
<type>setting</type>
<enabled>false</enabled>
</param>
<param name="tokenizationBINs" description="">
<type>list</type>
<enabled>true</enabled>
<BINs paymentSystem="MasterCard">
<BINrange start="522860"/>
<BINrange start="531310"/>
<BINrange start="533205"/>
<BINrange start="533208"/>
<BINrange start="536961"/>
<BINrange start="533669"/>
<BINrange start="545152"/>
<BINrange start="546901"/>
<BINrange start="546902" end="546913"/>
<BINrange start="546916" end="546918"/>
<BINrange start="546920"/>
<BINrange start="546922"/>
<BINrange start="546925" end="546933"/>
<BINrange start="546935"/>
<BINrange start="546937" end="546956"/>
<BINrange start="546959" end="546964"/>
<BINrange start="546966" end="546970"/>
<BINrange start="546972"/>
<BINrange start="546974" end="546977"/>
<BINrange start="546998" end="546999"/>
<BINrange start="547927"/>
<BINrange start="548401"/>
<BINrange start="548402" end="548403"/>
<BINrange start="548405" end="548407"/>
<BINrange start="548410" end="548413"/>
<BINrange start="548416"/>
<BINrange start="548420"/>
<BINrange start="548422"/>
<BINrange start="548425" end="548428"/>
<BINrange start="548430" end="548432"/>
<BINrange start="548435" end="548436"/>
<BINrange start="548438"/>
<BINrange start="548440"/>
<BINrange start="548442" end="548445"/>
<BINrange start="548447" end="548452"/>
<BINrange start="548454" end="548456"/>
<BINrange start="548459" end="548464"/>
<BINrange start="548466"/>
<BINrange start="548468" end="548469"/>
<BINrange start="548470"/>
<BINrange start="548472"/>
<BINrange start="548476" end="548477"/>
<BINrange start="548498" end="548499"/>
<BINrange start="557000"/>
</BINs>
<BINs paymentSystem="VISA">
<BINrange start="417398"/>
<BINrange start="427417"/>
<BINrange start="427427"/>
<BINrange start="427432"/>
<BINrange start="427448"/>
<BINrange start="427601" end="427613"/>
<BINrange start="427616" end="427618"/>
<BINrange start="427620"/>
<BINrange start="427622"/>
<BINrange start="427625" end="427633"/>
<BINrange start="427635" end="427646"/>
<BINrange start="427648" end="427656"/>
<BINrange start="427659" end="427664"/>
<BINrange start="427666" end="427670"/>
<BINrange start="427672"/>
<BINrange start="427674" end="427677"/>
<BINrange start="427680" end="427687"/>
<BINrange start="427689"/>
<BINrange start="427699"/>
<BINrange start="427901" end="427913"/>
<BINrange start="427916" end="427918"/>
<BINrange start="427920"/>
<BINrange start="427922"/>
<BINrange start="427925" end="427933"/>
<BINrange start="427935" end="427946"/>
<BINrange start="427948" end="427956"/>
<BINrange start="427959" end="427964"/>
<BINrange start="427966" end="427970"/>
<BINrange start="427972"/>
<BINrange start="427974" end="427975"/>
<BINrange start="427977"/>
<BINrange start="427999"/>
<BINrange start="481776"/>
<BINrange start="481779"/>
<BINrange start="481781"/>
<BINrange start="483983"/>
<BINrange start="485463"/>
</BINs>
</param>
<param name="mastercard_tokenisation" description="">
<type>setting</type>
<enabled>true</enabled>
</param>
<param name="visa_tokenisation" description="">
<type>setting</type>
<enabled>false</enabled>
</param>
<param name="visa_tokenization_new" description="">
<type>setting</type>
<enabled>true</enabled>
</param>
<param name="nfcTokensManagementMain" description="Управление жизненным циклом токенов">
<type>list</type>
<enabled>true</enabled>
<nfcTokensManagementVisa>true</nfcTokensManagementVisa>
<nfcTokensManagementMC>true</nfcTokensManagementMC>
</param>
<param name="statementWithLogo" description="Красивая выписка">
<type>setting</type>
<enabled>true</enabled>
</param>
<param name="birthday" description="">
<type>setting</type>
<enabled>false</enabled>
</param>
<param name="hidealfoperations" description="Скрываем операции АЛФ">
<type>setting</type>
<enabled>true</enabled>
</param>
<param name="aim_status" description="Индикация выполнения цели">
<type>setting</type>
<enabled>true</enabled>
</param>
<param name="MessengerPermissions" description="">
<type>list</type>
<authMessenger>true</authMessenger>
<MessengerNewYearPostcardURL>
https://test.stat.online.sberbank.ru/Dialogues/SberkotNewYear.mp4
</MessengerNewYearPostcardURL>
<MessengerNewYearPostcardText>Новый год — время чудес! Делитесь счастьем!</MessengerNewYearPostcardText>
<MessengerGiftsDefaultPostcardId>NewYear1</MessengerGiftsDefaultPostcardId>
<MessengerGiftsDefaultPostcardExtension>mp4</MessengerGiftsDefaultPostcardExtension>
<nodes>
<node id="node0.online.sberbank.ru">
<MessengerLoginNew>true</MessengerLoginNew>
<MessengerBlockContactWithReason>true</MessengerBlockContactWithReason>
<timeToRefreshUnread>600</timeToRefreshUnread>
<MessengerLinks>true</MessengerLinks>
<MessengerMarkdownLinks>true</MessengerMarkdownLinks>
<MessengerPostcardFirework>true</MessengerPostcardFirework>
<MessengerPostcardSend>true</MessengerPostcardSend>
<MessengerPostcardForNonClient>true</MessengerPostcardForNonClient>
<MessengerPostcardUGCVideo>true</MessengerPostcardUGCVideo>
<MessengerDocDoc>true</MessengerDocDoc>
<MessengerOpenDialogWithDeepLink>true</MessengerOpenDialogWithDeepLink>
<MessengerPin>true</MessengerPin>
<MessengerTyping>true</MessengerTyping>
<MessengerChatMute>true</MessengerChatMute>
<MessengerGroupChatEnabled>true</MessengerGroupChatEnabled>
<MessengerGroupChat>false</MessengerGroupChat>
<MessengerGroupChatAvatarLoadingEnabled>true</MessengerGroupChatAvatarLoadingEnabled>
<ChatWithBankLikeGroupchat>true</ChatWithBankLikeGroupchat>
<ChatWithBankNewYearEnabled>false</ChatWithBankNewYearEnabled>
<MessengerSaveContact>true</MessengerSaveContact>
<DraftMessagesEnabled>true</DraftMessagesEnabled>
<DraftMessage900Enabled>true</DraftMessage900Enabled>
<AttachmentsForChatBotEnabled>true</AttachmentsForChatBotEnabled>
<MessengerChannelsEnabled>true</MessengerChannelsEnabled>
</node>
<node id="node1.online.sberbank.ru">
<MessengerLoginNew>true</MessengerLoginNew>
<MessengerBlockContactWithReason>true</MessengerBlockContactWithReason>
<timeToRefreshUnread>600</timeToRefreshUnread>
<MessengerLinks>true</MessengerLinks>
<MessengerMarkdownLinks>true</MessengerMarkdownLinks>
<MessengerPostcardFirework>true</MessengerPostcardFirework>
<MessengerPostcardSend>true</MessengerPostcardSend>
<MessengerPostcardForNonClient>true</MessengerPostcardForNonClient>
<MessengerPostcardUGCVideo>true</MessengerPostcardUGCVideo>
<MessengerDocDoc>true</MessengerDocDoc>
<MessengerOpenDialogWithDeepLink>true</MessengerOpenDialogWithDeepLink>
<MessengerPin>true</MessengerPin>
<MessengerTyping>true</MessengerTyping>
<MessengerChatMute>true</MessengerChatMute>
<MessengerGroupChatEnabled>true</MessengerGroupChatEnabled>
<MessengerGroupChat>false</MessengerGroupChat>
<MessengerGroupChatAvatarLoadingEnabled>true</MessengerGroupChatAvatarLoadingEnabled>
<ChatWithBankLikeGroupchat>true</ChatWithBankLikeGroupchat>
<ChatWithBankNewYearEnabled>false</ChatWithBankNewYearEnabled>
<MessengerSaveContact>true</MessengerSaveContact>
<DraftMessagesEnabled>true</DraftMessagesEnabled>
<DraftMessage900Enabled>true</DraftMessage900Enabled>
<AttachmentsForChatBotEnabled>true</AttachmentsForChatBotEnabled>
<MessengerChannelsEnabled>true</MessengerChannelsEnabled>
</node>
<node id="node2.online.sberbank.ru">
<MessengerLoginNew>true</MessengerLoginNew>
<MessengerBlockContactWithReason>true</MessengerBlockContactWithReason>
<timeToRefreshUnread>600</timeToRefreshUnread>
<MessengerLinks>true</MessengerLinks>
<MessengerMarkdownLinks>true</MessengerMarkdownLinks>
<MessengerPostcardFirework>true</MessengerPostcardFirework>
<MessengerPostcardSend>true</MessengerPostcardSend>
<MessengerPostcardForNonClient>true</MessengerPostcardForNonClient>
<MessengerPostcardUGCVideo>true</MessengerPostcardUGCVideo>
<MessengerDocDoc>true</MessengerDocDoc>
<MessengerOpenDialogWithDeepLink>true</MessengerOpenDialogWithDeepLink>
<MessengerPin>true</MessengerPin>
<MessengerTyping>true</MessengerTyping>
<MessengerChatMute>true</MessengerChatMute>
<MessengerGroupChatEnabled>true</MessengerGroupChatEnabled>
<MessengerGroupChat>false</MessengerGroupChat>
<MessengerGroupChatAvatarLoadingEnabled>true</MessengerGroupChatAvatarLoadingEnabled>
<ChatWithBankLikeGroupchat>true</ChatWithBankLikeGroupchat>
<ChatWithBankNewYearEnabled>false</ChatWithBankNewYearEnabled>
<MessengerSaveContact>true</MessengerSaveContact>
<DraftMessagesEnabled>true</DraftMessagesEnabled>
<DraftMessage900Enabled>true</DraftMessage900Enabled>
<AttachmentsForChatBotEnabled>true</AttachmentsForChatBotEnabled>
<MessengerChannelsEnabled>true</MessengerChannelsEnabled>
</node>
<node id="node3.online.sberbank.ru">
<MessengerLoginNew>true</MessengerLoginNew>
<MessengerBlockContactWithReason>true</MessengerBlockContactWithReason>
<timeToRefreshUnread>600</timeToRefreshUnread>
<MessengerLinks>true</MessengerLinks>
<MessengerMarkdownLinks>true</MessengerMarkdownLinks>
<MessengerPostcardFirework>true</MessengerPostcardFirework>
<MessengerPostcardSend>true</MessengerPostcardSend>
<MessengerPostcardForNonClient>true</MessengerPostcardForNonClient>
<MessengerPostcardUGCVideo>true</MessengerPostcardUGCVideo>
<MessengerDocDoc>true</MessengerDocDoc>
<MessengerOpenDialogWithDeepLink>true</MessengerOpenDialogWithDeepLink>
<MessengerPin>true</MessengerPin>
<MessengerTyping>true</MessengerTyping>
<MessengerChatMute>true</MessengerChatMute>
<MessengerGroupChatEnabled>true</MessengerGroupChatEnabled>
<MessengerGroupChat>false</MessengerGroupChat>
<MessengerGroupChatAvatarLoadingEnabled>true</MessengerGroupChatAvatarLoadingEnabled>
<ChatWithBankLikeGroupchat>true</ChatWithBankLikeGroupchat>
<ChatWithBankNewYearEnabled>false</ChatWithBankNewYearEnabled>
<MessengerSaveContact>true</MessengerSaveContact>
<DraftMessagesEnabled>true</DraftMessagesEnabled>
<DraftMessage900Enabled>true</DraftMessage900Enabled>
<AttachmentsForChatBotEnabled>true</AttachmentsForChatBotEnabled>
<MessengerChannelsEnabled>true</MessengerChannelsEnabled>
</node>
<node id="node4.online.sberbank.ru">
<MessengerLoginNew>true</MessengerLoginNew>
<MessengerBlockContactWithReason>true</MessengerBlockContactWithReason>
<timeToRefreshUnread>600</timeToRefreshUnread>
<MessengerLinks>true</MessengerLinks>
<MessengerMarkdownLinks>true</MessengerMarkdownLinks>
<MessengerPostcardFirework>true</MessengerPostcardFirework>
<MessengerPostcardSend>true</MessengerPostcardSend>
<MessengerPostcardForNonClient>true</MessengerPostcardForNonClient>
<MessengerPostcardUGCVideo>true</MessengerPostcardUGCVideo>
<MessengerDocDoc>true</MessengerDocDoc>
<MessengerOpenDialogWithDeepLink>true</MessengerOpenDialogWithDeepLink>
<MessengerPin>true</MessengerPin>
<MessengerTyping>true</MessengerTyping>
<MessengerChatMute>true</MessengerChatMute>
<MessengerGroupChatEnabled>true</MessengerGroupChatEnabled>
<MessengerGroupChat>false</MessengerGroupChat>
<MessengerGroupChatAvatarLoadingEnabled>true</MessengerGroupChatAvatarLoadingEnabled>
<ChatWithBankLikeGroupchat>true</ChatWithBankLikeGroupchat>
<ChatWithBankNewYearEnabled>false</ChatWithBankNewYearEnabled>
<MessengerSaveContact>true</MessengerSaveContact>
<DraftMessagesEnabled>true</DraftMessagesEnabled>
<DraftMessage900Enabled>true</DraftMessage900Enabled>
<AttachmentsForChatBotEnabled>true</AttachmentsForChatBotEnabled>
<MessengerChannelsEnabled>true</MessengerChannelsEnabled>
</node>
<node id="greenfield1.online.sberbank.ru">
<MessengerLoginNew>true</MessengerLoginNew>
<MessengerBlockContactWithReason>true</MessengerBlockContactWithReason>
<timeToRefreshUnread>600</timeToRefreshUnread>
<MessengerLinks>true</MessengerLinks>
<MessengerMarkdownLinks>true</MessengerMarkdownLinks>
<MessengerPostcardFirework>true</MessengerPostcardFirework>
<MessengerPostcardSend>true</MessengerPostcardSend>
<MessengerPostcardForNonClient>true</MessengerPostcardForNonClient>
<MessengerPostcardUGCVideo>true</MessengerPostcardUGCVideo>
<MessengerDocDoc>true</MessengerDocDoc>
<MessengerOpenDialogWithDeepLink>true</MessengerOpenDialogWithDeepLink>
<MessengerPin>true</MessengerPin>
<MessengerTyping>true</MessengerTyping>
<MessengerChatMute>true</MessengerChatMute>
<MessengerGroupChatEnabled>true</MessengerGroupChatEnabled>
<MessengerGroupChat>false</MessengerGroupChat>
<MessengerGroupChatAvatarLoadingEnabled>true</MessengerGroupChatAvatarLoadingEnabled>
<ChatWithBankLikeGroupchat>true</ChatWithBankLikeGroupchat>
<ChatWithBankNewYearEnabled>false</ChatWithBankNewYearEnabled>
<MessengerSaveContact>true</MessengerSaveContact>
<DraftMessagesEnabled>true</DraftMessagesEnabled>
<DraftMessage900Enabled>true</DraftMessage900Enabled>
<AttachmentsForChatBotEnabled>true</AttachmentsForChatBotEnabled>
<MessengerChannelsEnabled>true</MessengerChannelsEnabled>
</node>
<node id="greenfield2.online.sberbank.ru">
<MessengerLoginNew>true</MessengerLoginNew>
<MessengerBlockContactWithReason>true</MessengerBlockContactWithReason>
<timeToRefreshUnread>600</timeToRefreshUnread>
<MessengerLinks>true</MessengerLinks>
<MessengerMarkdownLinks>true</MessengerMarkdownLinks>
<MessengerPostcardFirework>true</MessengerPostcardFirework>
<MessengerPostcardSend>true</MessengerPostcardSend>
<MessengerPostcardForNonClient>true</MessengerPostcardForNonClient>
<MessengerPostcardUGCVideo>true</MessengerPostcardUGCVideo>
<MessengerDocDoc>true</MessengerDocDoc>
<MessengerOpenDialogWithDeepLink>true</MessengerOpenDialogWithDeepLink>
<MessengerPin>true</MessengerPin>
<MessengerTyping>true</MessengerTyping>
<MessengerChatMute>true</MessengerChatMute>
<MessengerGroupChatEnabled>true</MessengerGroupChatEnabled>
<MessengerGroupChat>false</MessengerGroupChat>
<MessengerGroupChatAvatarLoadingEnabled>true</MessengerGroupChatAvatarLoadingEnabled>
<ChatWithBankLikeGroupchat>true</ChatWithBankLikeGroupchat>
<ChatWithBankNewYearEnabled>false</ChatWithBankNewYearEnabled>
<MessengerSaveContact>true</MessengerSaveContact>
<DraftMessagesEnabled>true</DraftMessagesEnabled>
<DraftMessage900Enabled>true</DraftMessage900Enabled>
<AttachmentsForChatBotEnabled>true</AttachmentsForChatBotEnabled>
<MessengerChannelsEnabled>true</MessengerChannelsEnabled>
</node>
<node id="ift-node1-mp.testonline.sberbank.ru">
<MessengerLoginNew>true</MessengerLoginNew>
<MessengerBlockContactWithReason>true</MessengerBlockContactWithReason>
<timeToRefreshUnread>600</timeToRefreshUnread>
<MessengerLinks>true</MessengerLinks>
<MessengerMarkdownLinks>true</MessengerMarkdownLinks>
<MessengerPostcardFirework>true</MessengerPostcardFirework>
<MessengerPostcardSend>true</MessengerPostcardSend>
<MessengerPostcardForNonClient>true</MessengerPostcardForNonClient>
<MessengerPostcardUGCVideo>true</MessengerPostcardUGCVideo>
<MessengerDocDoc>true</MessengerDocDoc>
<MessengerOpenDialogWithDeepLink>true</MessengerOpenDialogWithDeepLink>
<MessengerPin>true</MessengerPin>
<MessengerTyping>true</MessengerTyping>
<MessengerChatMute>true</MessengerChatMute>
<MessengerGroupChatEnabled>true</MessengerGroupChatEnabled>
<MessengerGroupChat>false</MessengerGroupChat>
<MessengerGroupChatAvatarLoadingEnabled>true</MessengerGroupChatAvatarLoadingEnabled>
<ChatWithBankLikeGroupchat>true</ChatWithBankLikeGroupchat>
<ChatWithBankNewYearEnabled>false</ChatWithBankNewYearEnabled>
<MessengerSaveContact>true</MessengerSaveContact>
<DraftMessagesEnabled>true</DraftMessagesEnabled>
<DraftMessage900Enabled>true</DraftMessage900Enabled>
<AttachmentsForChatBotEnabled>true</AttachmentsForChatBotEnabled>
<MessengerChannelsEnabled>true</MessengerChannelsEnabled>
</node>
<node id="ift-node2-mp.testonline.sberbank.ru">
<MessengerLoginNew>true</MessengerLoginNew>
<MessengerBlockContactWithReason>true</MessengerBlockContactWithReason>
<timeToRefreshUnread>600</timeToRefreshUnread>
<MessengerLinks>true</MessengerLinks>
<MessengerMarkdownLinks>true</MessengerMarkdownLinks>
<MessengerPostcardFirework>true</MessengerPostcardFirework>
<MessengerPostcardSend>true</MessengerPostcardSend>
<MessengerPostcardForNonClient>true</MessengerPostcardForNonClient>
<MessengerPostcardUGCVideo>true</MessengerPostcardUGCVideo>
<MessengerDocDoc>true</MessengerDocDoc>
<MessengerOpenDialogWithDeepLink>true</MessengerOpenDialogWithDeepLink>
<MessengerPin>true</MessengerPin>
<MessengerTyping>true</MessengerTyping>
<MessengerChatMute>true</MessengerChatMute>
<MessengerGroupChatEnabled>true</MessengerGroupChatEnabled>
<MessengerGroupChat>false</MessengerGroupChat>
<MessengerGroupChatAvatarLoadingEnabled>true</MessengerGroupChatAvatarLoadingEnabled>
<ChatWithBankLikeGroupchat>true</ChatWithBankLikeGroupchat>
<ChatWithBankNewYearEnabled>false</ChatWithBankNewYearEnabled>
<MessengerSaveContact>true</MessengerSaveContact>
<DraftMessagesEnabled>true</DraftMessagesEnabled>
<DraftMessage900Enabled>true</DraftMessage900Enabled>
<AttachmentsForChatBotEnabled>true</AttachmentsForChatBotEnabled>
<MessengerChannelsEnabled>true</MessengerChannelsEnabled>
</node>
<node id="mobile.sberbank.ru">
<MessengerLoginNew>true</MessengerLoginNew>
<MessengerBlockContactWithReason>true</MessengerBlockContactWithReason>
<timeToRefreshUnread>600</timeToRefreshUnread>
<MessengerLinks>true</MessengerLinks>
<MessengerMarkdownLinks>true</MessengerMarkdownLinks>
<MessengerPostcardFirework>true</MessengerPostcardFirework>
<MessengerPostcardSend>true</MessengerPostcardSend>
<MessengerPostcardForNonClient>true</MessengerPostcardForNonClient>
<MessengerPostcardUGCVideo>true</MessengerPostcardUGCVideo>
<MessengerDocDoc>true</MessengerDocDoc>
<MessengerOpenDialogWithDeepLink>true</MessengerOpenDialogWithDeepLink>
<MessengerPin>true</MessengerPin>
<MessengerTyping>true</MessengerTyping>
<MessengerChatMute>true</MessengerChatMute>
<MessengerGroupChatEnabled>true</MessengerGroupChatEnabled>
<MessengerGroupChat>false</MessengerGroupChat>
<MessengerGroupChatAvatarLoadingEnabled>true</MessengerGroupChatAvatarLoadingEnabled>
<ChatWithBankLikeGroupchat>true</ChatWithBankLikeGroupchat>
<ChatWithBankNewYearEnabled>false</ChatWithBankNewYearEnabled>
<MessengerSaveContact>true</MessengerSaveContact>
<DraftMessagesEnabled>true</DraftMessagesEnabled>
<DraftMessage900Enabled>true</DraftMessage900Enabled>
<AttachmentsForChatBotEnabled>true</AttachmentsForChatBotEnabled>
<MessengerChannelsEnabled>true</MessengerChannelsEnabled>
</node>
<node id="mobile.sberbank.ru:4459">
<MessengerLoginNew>true</MessengerLoginNew>
<MessengerBlockContactWithReason>true</MessengerBlockContactWithReason>
<timeToRefreshUnread>600</timeToRefreshUnread>
<MessengerLinks>true</MessengerLinks>
<MessengerMarkdownLinks>true</MessengerMarkdownLinks>
<MessengerPostcardFirework>true</MessengerPostcardFirework>
<MessengerPostcardSend>true</MessengerPostcardSend>
<MessengerPostcardForNonClient>true</MessengerPostcardForNonClient>
<MessengerPostcardUGCVideo>true</MessengerPostcardUGCVideo>
<MessengerDocDoc>true</MessengerDocDoc>
<MessengerOpenDialogWithDeepLink>true</MessengerOpenDialogWithDeepLink>
<MessengerPin>true</MessengerPin>
<MessengerTyping>true</MessengerTyping>
<MessengerChatMute>true</MessengerChatMute>
<MessengerGroupChatEnabled>true</MessengerGroupChatEnabled>
<MessengerGroupChat>false</MessengerGroupChat>
<MessengerGroupChatAvatarLoadingEnabled>true</MessengerGroupChatAvatarLoadingEnabled>
<ChatWithBankLikeGroupchat>true</ChatWithBankLikeGroupchat>
<ChatWithBankNewYearEnabled>false</ChatWithBankNewYearEnabled>
<MessengerSaveContact>true</MessengerSaveContact>
<DraftMessagesEnabled>true</DraftMessagesEnabled>
<DraftMessage900Enabled>true</DraftMessage900Enabled>
<AttachmentsForChatBotEnabled>true</AttachmentsForChatBotEnabled>
<MessengerChannelsEnabled>true</MessengerChannelsEnabled>
</node>
<node id="mobile.sberbank.ru:4460">
<MessengerLoginNew>true</MessengerLoginNew>
<MessengerBlockContactWithReason>true</MessengerBlockContactWithReason>
<timeToRefreshUnread>600</timeToRefreshUnread>
<MessengerLinks>true</MessengerLinks>
<MessengerMarkdownLinks>true</MessengerMarkdownLinks>
<MessengerPostcardFirework>true</MessengerPostcardFirework>
<MessengerPostcardSend>true</MessengerPostcardSend>
<MessengerPostcardForNonClient>true</MessengerPostcardForNonClient>
<MessengerPostcardUGCVideo>true</MessengerPostcardUGCVideo>
<MessengerDocDoc>true</MessengerDocDoc>
<MessengerOpenDialogWithDeepLink>true</MessengerOpenDialogWithDeepLink>
<MessengerPin>true</MessengerPin>
<MessengerTyping>true</MessengerTyping>
<MessengerChatMute>true</MessengerChatMute>
<MessengerGroupChatEnabled>true</MessengerGroupChatEnabled>
<MessengerGroupChat>false</MessengerGroupChat>
<MessengerGroupChatAvatarLoadingEnabled>false</MessengerGroupChatAvatarLoadingEnabled>
<ChatWithBankLikeGroupchat>true</ChatWithBankLikeGroupchat>
<ChatWithBankNewYearEnabled>true</ChatWithBankNewYearEnabled>
<MessengerSaveContact>true</MessengerSaveContact>
<DraftMessagesEnabled>false</DraftMessagesEnabled>
<DraftMessage900Enabled>true</DraftMessage900Enabled>
<AttachmentsForChatBotEnabled>true</AttachmentsForChatBotEnabled>
<MessengerChannelsEnabled>true</MessengerChannelsEnabled>
</node>
</nodes>
</param>
<param name="AccountClosing" description="Закрытие вкладов 8.0">
<type>setting</type>
<enabled>true</enabled>
</param>
<param name="local_tips" description="">
<type>setting</type>
<enabled>true</enabled>
</param>
<param name="pfmHosts" description="Список хостов для phizPFM">
<type>list</type>
<enabled>true</enabled>
<hosts>
<host id="node0.online.sberbank.ru">
<value>pfm.node0.online.sberbank.ru:4433</value>
</host>
<host id="node1.online.sberbank.ru">
<value>pfm.node1.online.sberbank.ru:4433</value>
</host>
<host id="node2.online.sberbank.ru">
<value>pfm.node2.online.sberbank.ru:4433</value>
</host>
<host id="node3.online.sberbank.ru">
<value>pfm.node3.online.sberbank.ru:4433</value>
</host>
<host id="greenfield1.online.sberbank.ru">
<value>greenfield1.online.sberbank.ru:6655</value>
</host>
<host id="greenfield2.online.sberbank.ru">
<value>greenfield2.online.sberbank.ru:6655</value>
</host>
<host id="194.186.207.23">
<value>194.186.207.23</value>
</host>
<host id="mobile.sberbank.ru">
<value>194.186.207.23</value>
</host>
<host id="ift-node1.testonline.sberbank.ru">
<value>pfm.ift-node1.testonline.sberbank.ru:4464</value>
</host>
<host id="ift-node1-mp.testonline.sberbank.ru">
<value>pfm.ift-node1.testonline.sberbank.ru:4464</value>
</host>
</hosts>
</param>
<param name="PFMConfigFlags" description="Блоки работают по логическому ИЛИ">
<PfmGlobal></PfmGlobal>
<PfmNodes>
<node id="node0.online.sberbank.ru">
<PFMSimilarSpendings>false</PFMSimilarSpendings>
<PFMUserParams>false</PFMUserParams>
<PFMOfferTips>false</PFMOfferTips>
<currentPfmApiVersion description="Устаревший параметр">1.30</currentPfmApiVersion>
<pfmApiVersion>1.30</pfmApiVersion>
<minAppVersionFromPFMApiVersion>9.1</minAppVersionFromPFMApiVersion>
<budget3_0Enabled>true</budget3_0Enabled>
<pfmDataOnline>true</pfmDataOnline>
<ALFInHistory>true</ALFInHistory>
<SendALFConnectInHistory>true</SendALFConnectInHistory>
</node>
<node id="node1.online.sberbank.ru">
<PFMSimilarSpendings>false</PFMSimilarSpendings>
<currentPfmApiVersion description="Устаревший параметр">1.30</currentPfmApiVersion>
<PFMUserParams>true</PFMUserParams>
<PFMOfferTips>false</PFMOfferTips>
<pfmApiVersion>1.40</pfmApiVersion>
<minAppVersionFromPFMApiVersion>9.1</minAppVersionFromPFMApiVersion>
<budget3_0Enabled>true</budget3_0Enabled>
<pfmDataOnline>true</pfmDataOnline>
<ALFInHistory>true</ALFInHistory>
<SendALFConnectInHistory>true</SendALFConnectInHistory>
</node>
<node id="node2.online.sberbank.ru">
<PFMSimilarSpendings>false</PFMSimilarSpendings>
<currentPfmApiVersion description="Устаревший параметр">1.30</currentPfmApiVersion>
<PFMUserParams>false</PFMUserParams>
<PFMOfferTips>false</PFMOfferTips>
<pfmApiVersion>1.40</pfmApiVersion>
<minAppVersionFromPFMApiVersion>8.15</minAppVersionFromPFMApiVersion>
<budget3_0Enabled>true</budget3_0Enabled>
<pfmDataOnline>true</pfmDataOnline>
<ALFInHistory>true</ALFInHistory>
<SendALFConnectInHistory>true</SendALFConnectInHistory>
</node>
<node id="node3.online.sberbank.ru">
<PFMSimilarSpendings>false</PFMSimilarSpendings>
<currentPfmApiVersion description="Устаревший параметр">1.30</currentPfmApiVersion>
<PFMUserParams>false</PFMUserParams>
<PFMOfferTips>false</PFMOfferTips>
<pfmApiVersion>1.40</pfmApiVersion>
<minAppVersionFromPFMApiVersion>8.15</minAppVersionFromPFMApiVersion>
<budget3_0Enabled>true</budget3_0Enabled>
<pfmDataOnline>true</pfmDataOnline>
<ALFInHistory>true</ALFInHistory>
<SendALFConnectInHistory>true</SendALFConnectInHistory>
</node>
<node id="node4.online.sberbank.ru">
<PFMSimilarSpendings>true</PFMSimilarSpendings>
<PFMUserParams>true</PFMUserParams>
<currentPfmApiVersion description="Устаревший параметр">1.30</currentPfmApiVersion>
<pfmApiVersion>1.40</pfmApiVersion>
<minAppVersionFromPFMApiVersion>9.1</minAppVersionFromPFMApiVersion>
<pfmDataOnline>true</pfmDataOnline>
</node>
<node id="greenfield1.online.sberbank.ru">
<PFMSimilarSpendings>true</PFMSimilarSpendings>
<currentPfmApiVersion description="Устаревший параметр">1.30</currentPfmApiVersion>
<PFMUserParams>false</PFMUserParams>
<PFMOfferTips>false</PFMOfferTips>
<pfmApiVersion>1.40</pfmApiVersion>
<minAppVersionFromPFMApiVersion>9.1</minAppVersionFromPFMApiVersion>
<budget3_0Enabled>true</budget3_0Enabled>
<pfmDataOnline>true</pfmDataOnline>
<ALFInHistory>true</ALFInHistory>
<SendALFConnectInHistory>true</SendALFConnectInHistory>
</node>
<node id="greenfield2.online.sberbank.ru">
<PFMSimilarSpendings>true</PFMSimilarSpendings>
<currentPfmApiVersion description="Устаревший параметр">1.30</currentPfmApiVersion>
<PFMUserParams>false</PFMUserParams>
<PFMOfferTips>false</PFMOfferTips>
<pfmApiVersion>1.40</pfmApiVersion>
<minAppVersionFromPFMApiVersion>9.1</minAppVersionFromPFMApiVersion>
<budget3_0Enabled>true</budget3_0Enabled>
<pfmDataOnline>true</pfmDataOnline>
<ALFInHistory>true</ALFInHistory>
<SendALFConnectInHistory>true</SendALFConnectInHistory>
</node>
<node id="194.186.207.23">
<PFMSimilarSpendings>true</PFMSimilarSpendings>
<currentPfmApiVersion description="Устаревший параметр">1.30</currentPfmApiVersion>
<PFMUserParams>true</PFMUserParams>
<PFMOfferTips>true</PFMOfferTips>
<pfmApiVersion>1.40</pfmApiVersion>
<minAppVersionFromPFMApiVersion>9.1</minAppVersionFromPFMApiVersion>
<budget3_0Enabled>true</budget3_0Enabled>
<pfmDataOnline>true</pfmDataOnline>
<ALFInHistory>true</ALFInHistory>
<SendALFConnectInHistory>true</SendALFConnectInHistory>
</node>
<node id="mobile.sberbank.ru">
<PFMSimilarSpendings>true</PFMSimilarSpendings>
<currentPfmApiVersion description="Устаревший параметр">1.30</currentPfmApiVersion>
<PFMUserParams>false</PFMUserParams>
<PFMOfferTips>true</PFMOfferTips>
<pfmApiVersion>1.40</pfmApiVersion>
<minAppVersionFromPFMApiVersion>9.1</minAppVersionFromPFMApiVersion>
<budget3_0Enabled>true</budget3_0Enabled>
<pfmDataOnline>true</pfmDataOnline>
<ALFInHistory>true</ALFInHistory>
<SendALFConnectInHistory>true</SendALFConnectInHistory>
</node>
<node id="ift-node1.testonline.sberbank.ru">
<PFMSimilarSpendings>true</PFMSimilarSpendings>
<currentPfmApiVersion description="Устаревший параметр">1.30</currentPfmApiVersion>
<PFMUserParams>false</PFMUserParams>
<PFMOfferTips>false</PFMOfferTips>
<pfmApiVersion>1.40</pfmApiVersion>
<minAppVersionFromPFMApiVersion>9.1</minAppVersionFromPFMApiVersion>
<budget3_0Enabled>true</budget3_0Enabled>
<pfmDataOnline>true</pfmDataOnline>
<ALFInHistory>true</ALFInHistory>
<SendALFConnectInHistory>true</SendALFConnectInHistory>
</node>
<node id="ift-node1-mp.testonline.sberbank.ru">
<PFMSimilarSpendings>true</PFMSimilarSpendings>
<currentPfmApiVersion description="Устаревший параметр">1.30</currentPfmApiVersion>
<PFMUserParams>false</PFMUserParams>
<PFMOfferTips>false</PFMOfferTips>
<pfmApiVersion>1.40</pfmApiVersion>
<minAppVersionFromPFMApiVersion>9.1</minAppVersionFromPFMApiVersion>
<budget3_0Enabled>true</budget3_0Enabled>
<pfmDataOnline>true</pfmDataOnline>
<ALFInHistory>true</ALFInHistory>
<SendALFConnectInHistory>true</SendALFConnectInHistory>
</node>
<node id="ift-node4.testonline.sberbank.ru">
<PFMSimilarSpendings>true</PFMSimilarSpendings>
<currentPfmApiVersion description="Устаревший параметр">1.30</currentPfmApiVersion>
<PFMUserParams>false</PFMUserParams>
<PFMOfferTips>true</PFMOfferTips>
<pfmApiVersion>1.40</pfmApiVersion>
<minAppVersionFromPFMApiVersion>9.1</minAppVersionFromPFMApiVersion>
<budget3_0Enabled>true</budget3_0Enabled>
<pfmDataOnline>true</pfmDataOnline>
<ALFInHistory>true</ALFInHistory>
<SendALFConnectInHistory>true</SendALFConnectInHistory>
</node>
<node id="ift-node4-mp.testonline.sberbank.ru">
<PFMSimilarSpendings>true</PFMSimilarSpendings>
<currentPfmApiVersion description="Устаревший параметр">1.30</currentPfmApiVersion>
<PFMUserParams>false</PFMUserParams>
<PFMOfferTips>true</PFMOfferTips>
<pfmApiVersion>1.40</pfmApiVersion>
<minAppVersionFromPFMApiVersion>9.1</minAppVersionFromPFMApiVersion>
<budget3_0Enabled>true</budget3_0Enabled>
<pfmDataOnline>true</pfmDataOnline>
<ALFInHistory>true</ALFInHistory>
<SendALFConnectInHistory>true</SendALFConnectInHistory>
</node>
<node id="ift-node2.testonline.sberbank.ru">
<PFMSimilarSpendings>true</PFMSimilarSpendings>
<currentPfmApiVersion description="Устаревший параметр">1.30</currentPfmApiVersion>
<PFMUserParams>false</PFMUserParams>
<PFMOfferTips>true</PFMOfferTips>
<pfmApiVersion>1.40</pfmApiVersion>
<minAppVersionFromPFMApiVersion>9.1</minAppVersionFromPFMApiVersion>
<budget3_0Enabled>true</budget3_0Enabled>
<pfmDataOnline>true</pfmDataOnline>
<ALFInHistory>true</ALFInHistory>
<SendALFConnectInHistory>true</SendALFConnectInHistory>
</node>
<node id="ift-node2-mp.testonline.sberbank.ru">
<PFMSimilarSpendings>true</PFMSimilarSpendings>
<currentPfmApiVersion description="Устаревший параметр">1.30</currentPfmApiVersion>
<PFMUserParams>false</PFMUserParams>
<PFMOfferTips>true</PFMOfferTips>
<pfmApiVersion>1.40</pfmApiVersion>
<minAppVersionFromPFMApiVersion>9.1</minAppVersionFromPFMApiVersion>
<budget3_0Enabled>true</budget3_0Enabled>
<pfmDataOnline>true</pfmDataOnline>
<ALFInHistory>true</ALFInHistory>
<SendALFConnectInHistory>true</SendALFConnectInHistory>
</node>
<node id="ift-node5.testonline.sberbank.ru">
<PFMSimilarSpendings>true</PFMSimilarSpendings>
<currentPfmApiVersion description="Устаревший параметр">1.30</currentPfmApiVersion>
<PFMUserParams>false</PFMUserParams>
<PFMOfferTips>true</PFMOfferTips>
<pfmApiVersion>1.40</pfmApiVersion>
<minAppVersionFromPFMApiVersion>9.1</minAppVersionFromPFMApiVersion>
<budget3_0Enabled>true</budget3_0Enabled>
<pfmDataOnline>true</pfmDataOnline>
<ALFInHistory>true</ALFInHistory>
<SendALFConnectInHistory>true</SendALFConnectInHistory>
</node>
<node id="ift-node5-mp.testonline.sberbank.ru">
<PFMSimilarSpendings>true</PFMSimilarSpendings>
<currentPfmApiVersion description="Устаревший параметр">1.30</currentPfmApiVersion>
<PFMUserParams>false</PFMUserParams>
<PFMOfferTips>true</PFMOfferTips>
<pfmApiVersion>1.40</pfmApiVersion>
<minAppVersionFromPFMApiVersion>9.1</minAppVersionFromPFMApiVersion>
<budget3_0Enabled>true</budget3_0Enabled>
<pfmDataOnline>true</pfmDataOnline>
<ALFInHistory>true</ALFInHistory>
<SendALFConnectInHistory>true</SendALFConnectInHistory>
</node>
</PfmNodes>
</param>
<param name="PFMTipsCloseEmptyQuizCount" description="Вероятность, с которой пользователю будет предложено выбрать причину скрытия совета">
<type>setting</type>
<enabled>false</enabled>
<value>0.25</value>
</param>
<param name="PFMDashboardIncomeHide" description="Дашборд, Доходы, скрытие АЛФ операций">
<type>list</type>
<enabledNodes>false</enabledNodes>
<enabledGlobal>true</enabledGlobal>
<PfmGlobal>
<dashboard>true</dashboard>
<income>true</income>
<hidealfoperations>true</hidealfoperations>
</PfmGlobal>
</param>
<param name="aim_close" description="Закрытие Цели">
<type>setting</type>
<enabled>true</enabled>
</param>
<param name="VOIPCallOperator" description="Звонок оператору через интернет">
<type>list</type>
<enabled>true</enabled>
<nodes>
<node id="node0.online.sberbank.ru">
<enabled>false</enabled>
<enabledPrelogin>false</enabledPrelogin>
<enabledPostlogin>false</enabledPostlogin>
<isHidingCallScreenEnabled>false</isHidingCallScreenEnabled>
<isInCallStatusBarEnabled>false</isInCallStatusBarEnabled>
<isVOIPSessionWarmupEnabled>false</isVOIPSessionWarmupEnabled>
<isVOIPNMTEnabled>false</isVOIPNMTEnabled>
</node>
<node id="node1.online.sberbank.ru">
<enabled>true</enabled>
<enabledPrelogin>true</enabledPrelogin>
<enabledPostlogin>true</enabledPostlogin>
<isHidingCallScreenEnabled>true</isHidingCallScreenEnabled>
<isInCallStatusBarEnabled>true</isInCallStatusBarEnabled>
<isVOIPSessionWarmupEnabled>true</isVOIPSessionWarmupEnabled>
<isVOIPNMTEnabled>true</isVOIPNMTEnabled>
<isChatWithBankCSIEnabled>true</isChatWithBankCSIEnabled>
</node>
<node id="node2.online.sberbank.ru">
<enabled>true</enabled>
<enabledPrelogin>true</enabledPrelogin>
<enabledPostlogin>true</enabledPostlogin>
<isHidingCallScreenEnabled>true</isHidingCallScreenEnabled>
<isInCallStatusBarEnabled>true</isInCallStatusBarEnabled>
<isVOIPSessionWarmupEnabled>true</isVOIPSessionWarmupEnabled>
<isVOIPNMTEnabled>true</isVOIPNMTEnabled>
<isChatWithBankCSIEnabled>true</isChatWithBankCSIEnabled>
</node>
<node id="node3.online.sberbank.ru">
<enabled>true</enabled>
<enabledPrelogin>true</enabledPrelogin>
<enabledPostlogin>true</enabledPostlogin>
<isHidingCallScreenEnabled>true</isHidingCallScreenEnabled>
<isInCallStatusBarEnabled>true</isInCallStatusBarEnabled>
<isVOIPSessionWarmupEnabled>true</isVOIPSessionWarmupEnabled>
<isVOIPNMTEnabled>true</isVOIPNMTEnabled>
<isChatWithBankCSIEnabled>true</isChatWithBankCSIEnabled>
</node>
<node id="greenfield1.online.sberbank.ru">
<enabled>true</enabled>
<enabledPrelogin>true</enabledPrelogin>
<enabledPostlogin>true</enabledPostlogin>
<isHidingCallScreenEnabled>true</isHidingCallScreenEnabled>
<isInCallStatusBarEnabled>true</isInCallStatusBarEnabled>
<isVOIPSessionWarmupEnabled>true</isVOIPSessionWarmupEnabled>
<isVOIPNMTEnabled>true</isVOIPNMTEnabled>
<isChatWithBankCSIEnabled>true</isChatWithBankCSIEnabled>
</node>
<node id="greenfield2.online.sberbank.ru">
<enabled>true</enabled>
<enabledPrelogin>true</enabledPrelogin>
<enabledPostlogin>true</enabledPostlogin>
<isHidingCallScreenEnabled>true</isHidingCallScreenEnabled>
<isInCallStatusBarEnabled>true</isInCallStatusBarEnabled>
<isVOIPSessionWarmupEnabled>true</isVOIPSessionWarmupEnabled>
<isVOIPNMTEnabled>true</isVOIPNMTEnabled>
<isChatWithBankCSIEnabled>true</isChatWithBankCSIEnabled>
</node>
<node id="194.186.207.23">
<enabled>true</enabled>
<enabledPrelogin>true</enabledPrelogin>
<enabledPostlogin>true</enabledPostlogin>
<isHidingCallScreenEnabled>true</isHidingCallScreenEnabled>
<isInCallStatusBarEnabled>true</isInCallStatusBarEnabled>
<isVOIPSessionWarmupEnabled>true</isVOIPSessionWarmupEnabled>
<isVOIPNMTEnabled>true</isVOIPNMTEnabled>
<isChatWithBankCSIEnabled>true</isChatWithBankCSIEnabled>
</node>
<node id="mobile.sberbank.ru">
<enabled>true</enabled>
<enabledPrelogin>true</enabledPrelogin>
<enabledPostlogin>true</enabledPostlogin>
<isHidingCallScreenEnabled>true</isHidingCallScreenEnabled>
<isInCallStatusBarEnabled>true</isInCallStatusBarEnabled>
<isVOIPSessionWarmupEnabled>true</isVOIPSessionWarmupEnabled>
<isVOIPNMTEnabled>true</isVOIPNMTEnabled>
<isChatWithBankCSIEnabled>true</isChatWithBankCSIEnabled>
</node>
<node id="ift-node1.testonline.sberbank.ru">
<enabled>true</enabled>
<enabledPrelogin>true</enabledPrelogin>
<enabledPostlogin>true</enabledPostlogin>
<isHidingCallScreenEnabled>true</isHidingCallScreenEnabled>
<isInCallStatusBarEnabled>true</isInCallStatusBarEnabled>
<isVOIPSessionWarmupEnabled>true</isVOIPSessionWarmupEnabled>
<isVOIPNMTEnabled>true</isVOIPNMTEnabled>
<isChatWithBankCSIEnabled>true</isChatWithBankCSIEnabled>
</node>
<node id="ift-node2.testonline.sberbank.ru">
<enabled>true</enabled>
<enabledPrelogin>true</enabledPrelogin>
<enabledPostlogin>true</enabledPostlogin>
<isHidingCallScreenEnabled>true</isHidingCallScreenEnabled>
<isInCallStatusBarEnabled>true</isInCallStatusBarEnabled>
<isVOIPSessionWarmupEnabled>true</isVOIPSessionWarmupEnabled>
<isVOIPNMTEnabled>true</isVOIPNMTEnabled>
<isChatWithBankCSIEnabled>true</isChatWithBankCSIEnabled>
</node>
<node id="ift-node1-mp.testonline.sberbank.ru">
<enabled>true</enabled>
<enabledPrelogin>true</enabledPrelogin>
<enabledPostlogin>true</enabledPostlogin>
<isHidingCallScreenEnabled>true</isHidingCallScreenEnabled>
<isInCallStatusBarEnabled>true</isInCallStatusBarEnabled>
<isVOIPSessionWarmupEnabled>true</isVOIPSessionWarmupEnabled>
<isVOIPNMTEnabled>true</isVOIPNMTEnabled>
<isChatWithBankCSIEnabled>true</isChatWithBankCSIEnabled>
</node>
<node id="ift-node2-mp.testonline.sberbank.ru">
<enabled>true</enabled>
<enabledPrelogin>true</enabledPrelogin>
<enabledPostlogin>true</enabledPostlogin>
<isHidingCallScreenEnabled>true</isHidingCallScreenEnabled>
<isInCallStatusBarEnabled>true</isInCallStatusBarEnabled>
<isVOIPSessionWarmupEnabled>true</isVOIPSessionWarmupEnabled>
<isVOIPNMTEnabled>true</isVOIPNMTEnabled>
<isChatWithBankCSIEnabled>true</isChatWithBankCSIEnabled>
</node>
<node id="ift-node4.testonline.sberbank.ru">
<enabled>true</enabled>
<enabledPrelogin>true</enabledPrelogin>
<enabledPostlogin>true</enabledPostlogin>
<isHidingCallScreenEnabled>true</isHidingCallScreenEnabled>
<isInCallStatusBarEnabled>true</isInCallStatusBarEnabled>
<isVOIPSessionWarmupEnabled>true</isVOIPSessionWarmupEnabled>
<isVOIPNMTEnabled>true</isVOIPNMTEnabled>
<isChatWithBankCSIEnabled>true</isChatWithBankCSIEnabled>
</node>
<node id="ift-node4-mp.testonline.sberbank.ru">
<enabled>true</enabled>
<enabledPrelogin>true</enabledPrelogin>
<enabledPostlogin>true</enabledPostlogin>
<isHidingCallScreenEnabled>true</isHidingCallScreenEnabled>
<isInCallStatusBarEnabled>true</isInCallStatusBarEnabled>
<isVOIPSessionWarmupEnabled>true</isVOIPSessionWarmupEnabled>
<isVOIPNMTEnabled>true</isVOIPNMTEnabled>
<isChatWithBankCSIEnabled>true</isChatWithBankCSIEnabled>
</node>
<node id="psinode1.testonline.sberbank.ru">
<enabled>true</enabled>
<enabledPrelogin>true</enabledPrelogin>
<enabledPostlogin>true</enabledPostlogin>
<isHidingCallScreenEnabled>true</isHidingCallScreenEnabled>
<isInCallStatusBarEnabled>true</isInCallStatusBarEnabled>
<isVOIPSessionWarmupEnabled>true</isVOIPSessionWarmupEnabled>
<isVOIPNMTEnabled>true</isVOIPNMTEnabled>
<isChatWithBankCSIEnabled>true</isChatWithBankCSIEnabled>
</node>
<node id="psinode2.testonline.sberbank.ru">
<enabled>true</enabled>
<enabledPrelogin>true</enabledPrelogin>
<enabledPostlogin>true</enabledPostlogin>
<isHidingCallScreenEnabled>true</isHidingCallScreenEnabled>
<isInCallStatusBarEnabled>true</isInCallStatusBarEnabled>
<isVOIPSessionWarmupEnabled>true</isVOIPSessionWarmupEnabled>
<isVOIPNMTEnabled>true</isVOIPNMTEnabled>
<isChatWithBankCSIEnabled>true</isChatWithBankCSIEnabled>
</node>
<node id="ift-node5.testonline.sberbank.ru">
<enabled>true</enabled>
<enabledPrelogin>true</enabledPrelogin>
<enabledPostlogin>true</enabledPostlogin>
<isHidingCallScreenEnabled>true</isHidingCallScreenEnabled>
<isInCallStatusBarEnabled>true</isInCallStatusBarEnabled>
<isVOIPSessionWarmupEnabled>true</isVOIPSessionWarmupEnabled>
<isVOIPNMTEnabled>true</isVOIPNMTEnabled>
<isChatWithBankCSIEnabled>true</isChatWithBankCSIEnabled>
</node>
<node id="ift-node5-mp.testonline.sberbank.ru">
<enabled>true</enabled>
<enabledPrelogin>true</enabledPrelogin>
<enabledPostlogin>true</enabledPostlogin>
<isHidingCallScreenEnabled>true</isHidingCallScreenEnabled>
<isInCallStatusBarEnabled>true</isInCallStatusBarEnabled>
<isVOIPSessionWarmupEnabled>true</isVOIPSessionWarmupEnabled>
<isVOIPNMTEnabled>true</isVOIPNMTEnabled>
<isChatWithBankCSIEnabled>true</isChatWithBankCSIEnabled>
</node>
</nodes>
</param>
<param name="ChatBot" description="Диалог с контактом Сбербанк (@900)">
<type>list</type>
<enabled>true</enabled>
<nodes>
<node id="node0.online.sberbank.ru">
<dialog900>true</dialog900>
<SmartSearchChatWithBankEnabled>true</SmartSearchChatWithBankEnabled>
</node>
<node id="node1.online.sberbank.ru">
<dialog900>true</dialog900>
<SmartSearchChatWithBankEnabled>true</SmartSearchChatWithBankEnabled>
</node>
<node id="node2.online.sberbank.ru">
<dialog900>true</dialog900>
<SmartSearchChatWithBankEnabled>true</SmartSearchChatWithBankEnabled>
</node>
<node id="node3.online.sberbank.ru">
<dialog900>true</dialog900>
<SmartSearchChatWithBankEnabled>true</SmartSearchChatWithBankEnabled>
</node>
<node id="greenfield1.online.sberbank.ru">
<dialog900>true</dialog900>
<SmartSearchChatWithBankEnabled>true</SmartSearchChatWithBankEnabled>
</node>
<node id="greenfield2.online.sberbank.ru">
<dialog900>true</dialog900>
<SmartSearchChatWithBankEnabled>true</SmartSearchChatWithBankEnabled>
</node>
<node id="mobile.sberbank.ru">
<dialog900>true</dialog900>
<SmartSearchChatWithBankEnabled>true</SmartSearchChatWithBankEnabled>
</node>
<node id="ift-node1.testonline.sberbank.ru">
<dialog900>true</dialog900>
<SmartSearchChatWithBankEnabled>true</SmartSearchChatWithBankEnabled>
</node>
<node id="ift-node2.testonline.sberbank.ru">
<dialog900>true</dialog900>
<SmartSearchChatWithBankEnabled>true</SmartSearchChatWithBankEnabled>
</node>
<node id="ift-node1-mp.testonline.sberbank.ru">
<dialog900>true</dialog900>
<SmartSearchChatWithBankEnabled>true</SmartSearchChatWithBankEnabled>
</node>
<node id="ift-node2-mp.testonline.sberbank.ru">
<dialog900>true</dialog900>
<SmartSearchChatWithBankEnabled>true</SmartSearchChatWithBankEnabled>
</node>
<node id="ift-node4.testonline.sberbank.ru">
<dialog900>true</dialog900>
<SmartSearchChatWithBankEnabled>true</SmartSearchChatWithBankEnabled>
</node>
<node id="ift-node4-mp.testonline.sberbank.ru">
<dialog900>true</dialog900>
<SmartSearchChatWithBankEnabled>true</SmartSearchChatWithBankEnabled>
</node>
<node id="ift-node5.testonline.sberbank.ru">
<dialog900>true</dialog900>
<SmartSearchChatWithBankEnabled>true</SmartSearchChatWithBankEnabled>
</node>
<node id="ift-node5-mp.testonline.sberbank.ru">
<dialog900>true</dialog900>
<SmartSearchChatWithBankEnabled>true</SmartSearchChatWithBankEnabled>
</node>
<node id="psinode1.testonline.sberbank.ru">
<dialog900>true</dialog900>
<SmartSearchChatWithBankEnabled>true</SmartSearchChatWithBankEnabled>
</node>
<node id="psinode2.testonline.sberbank.ru">
<dialog900>true</dialog900>
<SmartSearchChatWithBankEnabled>true</SmartSearchChatWithBankEnabled>
</node>
</nodes>
</param>
<param name="900Permissions" description="">
<type>list</type>
<pushAlertTimeInterval>86400</pushAlertTimeInterval>
<efsMobileBank>true</efsMobileBank>
<nodes>
<node id="ift-node1.testonline.sberbank.ru">
<efsMobileBank>true</efsMobileBank>
</node>
<node id="ift-node2.testonline.sberbank.ru">
<efsMobileBank>true</efsMobileBank>
</node>
<node id="ift-node1-mp.testonline.sberbank.ru">
<efsMobileBank>true</efsMobileBank>
<pushAlertEnabled>true</pushAlertEnabled>
</node>
<node id="ift-node2-mp.testonline.sberbank.ru">
<efsMobileBank>true</efsMobileBank>
<pushAlertEnabled>true</pushAlertEnabled>
</node>
<node id="node0.online.sberbank.ru">
<pushAlertEnabled>true</pushAlertEnabled>
</node>
<node id="node1.online.sberbank.ru">
<pushAlertEnabled>true</pushAlertEnabled>
</node>
<node id="node2.online.sberbank.ru">
<pushAlertEnabled>true</pushAlertEnabled>
</node>
<node id="node3.online.sberbank.ru">
<pushAlertEnabled>true</pushAlertEnabled>
</node>
<node id="greenfield1.online.sberbank.ru">
<pushAlertEnabled>true</pushAlertEnabled>
<efsMobileBank>true</efsMobileBank>
</node>
<node id="greenfield2.online.sberbank.ru">
<pushAlertEnabled>true</pushAlertEnabled>
</node>
<node id="194.186.207.23">
<pushAlertEnabled>true</pushAlertEnabled>
</node>
<node id="mobile.sberbank.ru">
<pushAlertEnabled>true</pushAlertEnabled>
<efsMobileBank>true</efsMobileBank>
</node>
</nodes>
</param>
<param name="CorePermissions" description="">
<type>list</type>
<enabled>true</enabled>
<nodes>
<node id="node0.online.sberbank.ru">
<coreQR>false</coreQR>
<SBTelecom>true</SBTelecom>
<CreditRating>false</CreditRating>
<CreditRating_v2>false</CreditRating_v2>
<OKBRating>false</OKBRating>
<EnableBetaVersion>
<version>8.1.2</version>
<version>8.1.1</version>
</EnableBetaVersion>
<enableArrests>true</enableArrests>
<cardDelivery>true</cardDelivery>
<loanTable>true</loanTable>
<hideRegion>true</hideRegion>
<pciDss>true</pciDss>
<cashByCode>false</cashByCode>
<selfTransfer>false</selfTransfer>
<selfTransferStorno>false</selfTransferStorno>
<creditCardAutorepayment>true</creditCardAutorepayment>
<blockedCardsStatusWay4>true</blockedCardsStatusWay4>
<governmentServices_actual>true</governmentServices_actual>
<pensionTransfer_actual>true</pensionTransfer_actual>
<pensionCertificate_actual>true</pensionCertificate_actual>
<governmentServices>true</governmentServices>
<pensionTransfer>true</pensionTransfer>
<pensionCertificate>true</pensionCertificate>
<pensionRegistration>true</pensionRegistration>
<governmentAnimationSearching>true</governmentAnimationSearching>
<blockedCardsStatusWay4>true</blockedCardsStatusWay4>
<autoTransfer>true</autoTransfer>
<UFSHost/>
<coreCreditCardInfo_v2>true</coreCreditCardInfo_v2>
<coreCreditCardInfo_v3>true</coreCreditCardInfo_v3>
<OmniChannelHistory>true</OmniChannelHistory>
<showUfsHistoryOperations>false</showUfsHistoryOperations>
<showSpasibo>true</showSpasibo>
<enableContactMangager>true</enableContactMangager>
<AuthCyrrilicKeypadEnabled>true</AuthCyrrilicKeypadEnabled>
<showCorporateCard>true</showCorporateCard>
<autoTouchID>true</autoTouchID>
<suggestionsEnabled>true</suggestionsEnabled>
<historyList_v2>false</historyList_v2>
<shimmersEnabled>true</shimmersEnabled>
<skeletonsEnabled>true</skeletonsEnabled>
<early2018EnterAnimation>true</early2018EnterAnimation>
<fastLoginOnMessengerPushEnabled>true</fastLoginOnMessengerPushEnabled>
<currenciesInOperationsVCEnabled>false</currenciesInOperationsVCEnabled>
<EribPenaltyDocumentsSavingAllowed>true</EribPenaltyDocumentsSavingAllowed>
<EribFinesLoadingAutoretry>true</EribFinesLoadingAutoretry>
<EribStatePaymentShortCutsEnabled>true</EribStatePaymentShortCutsEnabled>
<EribAfterPayInfoEnabled>true</EribAfterPayInfoEnabled>
<EribServicesDeeplinkEnabled>true</EribServicesDeeplinkEnabled>
<EribPenaltyInPaymentProcessEnabled>true</EribPenaltyInPaymentProcessEnabled>
<EribPenaltyDocumentsMigration>true</EribPenaltyDocumentsMigration>
<overseasTransfer>true</overseasTransfer>
<importantInfoEnabled>false</importantInfoEnabled>
<historyRouterEnabled>true</historyRouterEnabled>
<SBTelecomSectionOnlyForClients>false</SBTelecomSectionOnlyForClients>
<webAnalyticsEnabled>true</webAnalyticsEnabled>
<newSectionInvestEnable>true</newSectionInvestEnable>
<newProductsVC>true</newProductsVC>
<newProductsVCv2>true</newProductsVCv2>
<hidingSectionEnabled>true</hidingSectionEnabled>
<orderingSectionEnabled>true</orderingSectionEnabled>
<hidingSectionTutorialEnabled>false</hidingSectionTutorialEnabled>
<FastLoginApp>false</FastLoginApp>
<PrintAutoSubscriptionCheck>false</PrintAutoSubscriptionCheck>
<productNavigationBarMod>3</productNavigationBarMod>
<IsFromAddrBook>true</IsFromAddrBook>
<InstantApp>false</InstantApp>
<InstantAppV2>true</InstantAppV2>
<mobilePOSEnabled>true</mobilePOSEnabled>
<earlyLoanRepayment>true</earlyLoanRepayment>
<newProductDetailsUIEnabled>true</newProductDetailsUIEnabled>
<newProductDetailsContentEnabled>true</newProductDetailsContentEnabled>
<soundsInAppEnabled>true</soundsInAppEnabled>
<PaymentTransactionsPopUpConfirmNumber>true</PaymentTransactionsPopUpConfirmNumber>
<googleMapsEnabled>false</googleMapsEnabled>
<messengerFirstLoginEnabled>false</messengerFirstLoginEnabled>
<authBlockingScreen>true</authBlockingScreen>
<PrintAutoSubscriptionTutorialCheck>true</PrintAutoSubscriptionTutorialCheck>
<balanceFromPush>true</balanceFromPush>
</node>
<node id="ift-node0.online.sberbank.ru">
<coreQR>false</coreQR>
<SBTelecom>true</SBTelecom>
<CreditRating>false</CreditRating>
<CreditRating_v2>false</CreditRating_v2>
<OKBRating>false</OKBRating>
<EnableBetaVersion>
<version>8.1.2</version>
<version>8.1.1</version>
</EnableBetaVersion>
<enableArrests>true</enableArrests>
<cardDelivery>true</cardDelivery>
<loanTable>true</loanTable>
<hideRegion>true</hideRegion>
<pciDss>true</pciDss>
<cashByCode>false</cashByCode>
<selfTransfer>false</selfTransfer>
<selfTransferStorno>false</selfTransferStorno>
<creditCardAutorepayment>true</creditCardAutorepayment>
<blockedCardsStatusWay4>true</blockedCardsStatusWay4>
<governmentServices_actual>true</governmentServices_actual>
<pensionTransfer_actual>true</pensionTransfer_actual>
<pensionCertificate_actual>true</pensionCertificate_actual>
<governmentServices>true</governmentServices>
<pensionTransfer>true</pensionTransfer>
<pensionCertificate>true</pensionCertificate>
<pensionRegistration>true</pensionRegistration>
<governmentAnimationSearching>true</governmentAnimationSearching>
<blockedCardsStatusWay4>true</blockedCardsStatusWay4>
<autoTransfer>true</autoTransfer>
<UFSHost/>
<coreCreditCardInfo_v2>true</coreCreditCardInfo_v2>
<coreCreditCardInfo_v3>true</coreCreditCardInfo_v3>
<OmniChannelHistory>true</OmniChannelHistory>
<showUfsHistoryOperations>false</showUfsHistoryOperations>
<showSpasibo>true</showSpasibo>
<enableContactMangager>true</enableContactMangager>
<AuthCyrrilicKeypadEnabled>true</AuthCyrrilicKeypadEnabled>
<showCorporateCard>true</showCorporateCard>
<autoTouchID>true</autoTouchID>
<suggestionsEnabled>true</suggestionsEnabled>
<historyList_v2>false</historyList_v2>
<shimmersEnabled>true</shimmersEnabled>
<skeletonsEnabled>true</skeletonsEnabled>
<early2018EnterAnimation>true</early2018EnterAnimation>
<fastLoginOnMessengerPushEnabled>true</fastLoginOnMessengerPushEnabled>
<currenciesInOperationsVCEnabled>false</currenciesInOperationsVCEnabled>
<EribPenaltyDocumentsSavingAllowed>true</EribPenaltyDocumentsSavingAllowed>
<EribFinesLoadingAutoretry>true</EribFinesLoadingAutoretry>
<EribStatePaymentShortCutsEnabled>true</EribStatePaymentShortCutsEnabled>
<EribAfterPayInfoEnabled>true</EribAfterPayInfoEnabled>
<EribServicesDeeplinkEnabled>true</EribServicesDeeplinkEnabled>
<EribPenaltyInPaymentProcessEnabled>true</EribPenaltyInPaymentProcessEnabled>
<EribPenaltyDocumentsMigration>true</EribPenaltyDocumentsMigration>
<overseasTransfer>true</overseasTransfer>
<importantInfoEnabled>false</importantInfoEnabled>
<historyRouterEnabled>true</historyRouterEnabled>
<SBTelecomSectionOnlyForClients>false</SBTelecomSectionOnlyForClients>
<webAnalyticsEnabled>true</webAnalyticsEnabled>
<newSectionInvestEnable>true</newSectionInvestEnable>
<newProductsVC>true</newProductsVC>
<newProductsVCv2>true</newProductsVCv2>
<hidingSectionEnabled>true</hidingSectionEnabled>
<orderingSectionEnabled>true</orderingSectionEnabled>
<hidingSectionTutorialEnabled>false</hidingSectionTutorialEnabled>
<FastLoginApp>false</FastLoginApp>
<PrintAutoSubscriptionCheck>false</PrintAutoSubscriptionCheck>
<productNavigationBarMod>3</productNavigationBarMod>
<IsFromAddrBook>true</IsFromAddrBook>
<InstantApp>false</InstantApp>
<InstantAppV2>true</InstantAppV2>
<mobilePOSEnabled>true</mobilePOSEnabled>
<earlyLoanRepayment>true</earlyLoanRepayment>
<newProductDetailsUIEnabled>true</newProductDetailsUIEnabled>
<newProductDetailsContentEnabled>true</newProductDetailsContentEnabled>
<soundsInAppEnabled>true</soundsInAppEnabled>
<PaymentTransactionsPopUpConfirmNumber>true</PaymentTransactionsPopUpConfirmNumber>
<googleMapsEnabled>false</googleMapsEnabled>
<messengerFirstLoginEnabled>false</messengerFirstLoginEnabled>
<authBlockingScreen>true</authBlockingScreen>
<PrintAutoSubscriptionTutorialCheck>true</PrintAutoSubscriptionTutorialCheck>
<balanceFromPush>true</balanceFromPush>
</node>
<node id="node1.online.sberbank.ru">
<coreQR>true</coreQR>
<SBTelecom>true</SBTelecom>
<CreditRating>false</CreditRating>
<CreditRating_v2>false</CreditRating_v2>
<OKBRating>false</OKBRating>
<EnableBetaVersion>
<version>8.1.2</version>
<version>8.1.1</version>
</EnableBetaVersion>
<enableArrests>true</enableArrests>
<cardDelivery>true</cardDelivery>
<loanTable>true</loanTable>
<hideRegion>true</hideRegion>
<pciDss>true</pciDss>
<cashByCode>false</cashByCode>
<selfTransfer>false</selfTransfer>
<selfTransferStorno>false</selfTransferStorno>
<creditCardAutorepayment>true</creditCardAutorepayment>
<governmentServices>true</governmentServices>
<pensionTransfer>true</pensionTransfer>
<pensionCertificate>true</pensionCertificate>
<governmentServices_actual>true</governmentServices_actual>
<pensionTransfer_actual>true</pensionTransfer_actual>
<pensionCertificate_actual>true</pensionCertificate_actual>
<pensionRegistration>true</pensionRegistration>
<governmentAnimationSearching>true</governmentAnimationSearching>
<blockedCardsStatusWay4>true</blockedCardsStatusWay4>
<autoTransfer>true</autoTransfer>
<UFSHost/>
<coreCreditCardInfo_v2>true</coreCreditCardInfo_v2>
<coreCreditCardInfo_v3>true</coreCreditCardInfo_v3>
<OmniChannelHistory>true</OmniChannelHistory>
<showUfsHistoryOperations>false</showUfsHistoryOperations>
<showSpasibo>true</showSpasibo>
<enableContactMangager>true</enableContactMangager>
<AuthCyrrilicKeypadEnabled>true</AuthCyrrilicKeypadEnabled>
<showCorporateCard>true</showCorporateCard>
<autoTouchID>true</autoTouchID>
<suggestionsEnabled>true</suggestionsEnabled>
<historyList_v2>true</historyList_v2>
<shimmersEnabled>true</shimmersEnabled>
<skeletonsEnabled>true</skeletonsEnabled>
<early2018EnterAnimation>true</early2018EnterAnimation>
<fastLoginOnMessengerPushEnabled>true</fastLoginOnMessengerPushEnabled>
<currenciesInOperationsVCEnabled>false</currenciesInOperationsVCEnabled>
<EribPenaltyDocumentsSavingAllowed>true</EribPenaltyDocumentsSavingAllowed>
<EribFinesLoadingAutoretry>true</EribFinesLoadingAutoretry>
<EribStatePaymentShortCutsEnabled>true</EribStatePaymentShortCutsEnabled>
<EribAfterPayInfoEnabled>true</EribAfterPayInfoEnabled>
<EribServicesDeeplinkEnabled>true</EribServicesDeeplinkEnabled>
<EribPenaltyInPaymentProcessEnabled>true</EribPenaltyInPaymentProcessEnabled>
<EribPenaltyDocumentsMigration>true</EribPenaltyDocumentsMigration>
<charity>
<enabled>true</enabled>
<billing>284</billing>
<provider>621180</provider>
<service>297</service>
<text>
Здесь можно перевести любую сумму пострадавшим в Кемерове
</text>
</charity>
<overseasTransfer>true</overseasTransfer>
<importantInfoEnabled>false</importantInfoEnabled>
<historyRouterEnabled>true</historyRouterEnabled>
<SBTelecomSectionOnlyForClients>false</SBTelecomSectionOnlyForClients>
<webAnalyticsEnabled>true</webAnalyticsEnabled>
<newSectionInvestEnable>true</newSectionInvestEnable>
<newProductsVC>true</newProductsVC>
<newProductsVCv2>true</newProductsVCv2>
<hidingSectionEnabled>true</hidingSectionEnabled>
<orderingSectionEnabled>true</orderingSectionEnabled>
<hidingSectionTutorialEnabled>false</hidingSectionTutorialEnabled>
<FastLoginApp>false</FastLoginApp>
<PrintAutoSubscriptionCheck>false</PrintAutoSubscriptionCheck>
<productNavigationBarMod>3</productNavigationBarMod>
<IsFromAddrBook>true</IsFromAddrBook>
<InstantApp>true</InstantApp>
<InstantAppV2>true</InstantAppV2>
<mobilePOSEnabled>true</mobilePOSEnabled>
<earlyLoanRepayment>true</earlyLoanRepayment>
<newProductDetailsUIEnabled>true</newProductDetailsUIEnabled>
<newProductDetailsContentEnabled>true</newProductDetailsContentEnabled>
<soundsInAppEnabled>true</soundsInAppEnabled>
<PaymentTransactionsPopUpConfirmNumber>true</PaymentTransactionsPopUpConfirmNumber>
<googleMapsEnabled>false</googleMapsEnabled>
<messengerFirstLoginEnabled>false</messengerFirstLoginEnabled>
<authBlockingScreen>true</authBlockingScreen>
<balanceFromPush>true</balanceFromPush>
</node>
<node id="node2.online.sberbank.ru">
<coreQR>true</coreQR>
<SBTelecom>true</SBTelecom>
<CreditRating>false</CreditRating>
<CreditRating_v2>false</CreditRating_v2>
<OKBRating>false</OKBRating>
<EnableBetaVersion>
<version>8.1.2</version>
<version>8.1.1</version>
</EnableBetaVersion>
<enableArrests>true</enableArrests>
<cardDelivery>true</cardDelivery>
<loanTable>true</loanTable>
<hideRegion>true</hideRegion>
<pciDss>true</pciDss>
<cashByCode>false</cashByCode>
<selfTransfer>false</selfTransfer>
<selfTransferStorno>false</selfTransferStorno>
<creditCardAutorepayment>true</creditCardAutorepayment>
<governmentServices>true</governmentServices>
<pensionTransfer>true</pensionTransfer>
<pensionCertificate>true</pensionCertificate>
<governmentServices_actual>true</governmentServices_actual>
<pensionTransfer_actual>true</pensionTransfer_actual>
<pensionCertificate_actual>true</pensionCertificate_actual>
<pensionRegistration>true</pensionRegistration>
<governmentAnimationSearching>true</governmentAnimationSearching>
<blockedCardsStatusWay4>true</blockedCardsStatusWay4>
<autoTransfer>true</autoTransfer>
<UFSHost/>
<coreCreditCardInfo_v2>true</coreCreditCardInfo_v2>
<coreCreditCardInfo_v3>true</coreCreditCardInfo_v3>
<OmniChannelHistory>true</OmniChannelHistory>
<showUfsHistoryOperations>false</showUfsHistoryOperations>
<showSpasibo>true</showSpasibo>
<enableContactMangager>true</enableContactMangager>
<AuthCyrrilicKeypadEnabled>true</AuthCyrrilicKeypadEnabled>
<showCorporateCard>true</showCorporateCard>
<autoTouchID>true</autoTouchID>
<suggestionsEnabled>true</suggestionsEnabled>
<historyList_v2>true</historyList_v2>
<shimmersEnabled>true</shimmersEnabled>
<skeletonsEnabled>true</skeletonsEnabled>
<early2018EnterAnimation>true</early2018EnterAnimation>
<fastLoginOnMessengerPushEnabled>true</fastLoginOnMessengerPushEnabled>
<currenciesInOperationsVCEnabled>false</currenciesInOperationsVCEnabled>
<EribPenaltyDocumentsSavingAllowed>true</EribPenaltyDocumentsSavingAllowed>
<EribFinesLoadingAutoretry>true</EribFinesLoadingAutoretry>
<EribStatePaymentShortCutsEnabled>true</EribStatePaymentShortCutsEnabled>
<EribAfterPayInfoEnabled>true</EribAfterPayInfoEnabled>
<EribServicesDeeplinkEnabled>true</EribServicesDeeplinkEnabled>
<EribPenaltyInPaymentProcessEnabled>true</EribPenaltyInPaymentProcessEnabled>
<EribPenaltyDocumentsMigration>true</EribPenaltyDocumentsMigration>
<charity>
<enabled>true</enabled>
<billing>284</billing>
<provider>500438244</provider>
<service>297</service>
<text>
Здесь можно перевести любую сумму пострадавшим в Кемерове
</text>
</charity>
<overseasTransfer>true</overseasTransfer>
<importantInfoEnabled>false</importantInfoEnabled>
<historyRouterEnabled>true</historyRouterEnabled>
<SBTelecomSectionOnlyForClients>false</SBTelecomSectionOnlyForClients>
<webAnalyticsEnabled>true</webAnalyticsEnabled>
<newSectionInvestEnable>true</newSectionInvestEnable>
<newProductsVC>true</newProductsVC>
<newProductsVCv2>true</newProductsVCv2>
<hidingSectionEnabled>true</hidingSectionEnabled>
<orderingSectionEnabled>true</orderingSectionEnabled>
<hidingSectionTutorialEnabled>false</hidingSectionTutorialEnabled>
<FastLoginApp>false</FastLoginApp>
<PrintAutoSubscriptionCheck>false</PrintAutoSubscriptionCheck>
<productNavigationBarMod>3</productNavigationBarMod>
<IsFromAddrBook>true</IsFromAddrBook>
<InstantApp>true</InstantApp>
<InstantAppV2>true</InstantAppV2>
<mobilePOSEnabled>true</mobilePOSEnabled>
<earlyLoanRepayment>true</earlyLoanRepayment>
<newProductDetailsUIEnabled>true</newProductDetailsUIEnabled>
<newProductDetailsContentEnabled>true</newProductDetailsContentEnabled>
<soundsInAppEnabled>true</soundsInAppEnabled>
<PaymentTransactionsPopUpConfirmNumber>true</PaymentTransactionsPopUpConfirmNumber>
<googleMapsEnabled>false</googleMapsEnabled>
<messengerFirstLoginEnabled>false</messengerFirstLoginEnabled>
<authBlockingScreen>true</authBlockingScreen>
<PrintAutoSubscriptionTutorialCheck>true</PrintAutoSubscriptionTutorialCheck>
<balanceFromPush>true</balanceFromPush>
</node>
<node id="node3.online.sberbank.ru">
<coreQR>true</coreQR>
<SBTelecom>true</SBTelecom>
<CreditRating>false</CreditRating>
<CreditRating_v2>false</CreditRating_v2>
<OKBRating>false</OKBRating>
<EnableBetaVersion>
<version>8.1.2</version>
<version>8.1.1</version>
</EnableBetaVersion>
<enableArrests>true</enableArrests>
<cardDelivery>true</cardDelivery>
<loanTable>true</loanTable>
<hideRegion>true</hideRegion>
<pciDss>true</pciDss>
<cashByCode>false</cashByCode>
<selfTransfer>false</selfTransfer>
<selfTransferStorno>false</selfTransferStorno>
<creditCardAutorepayment>true</creditCardAutorepayment>
<coreCreditCardInfo_v2>true</coreCreditCardInfo_v2>
<coreCreditCardInfo_v3>true</coreCreditCardInfo_v3>
<OmniChannelHistory>true</OmniChannelHistory>
<governmentServices>true</governmentServices>
<pensionTransfer>true</pensionTransfer>
<pensionCertificate>true</pensionCertificate>
<governmentServices_actual>true</governmentServices_actual>
<pensionTransfer_actual>true</pensionTransfer_actual>
<pensionCertificate_actual>true</pensionCertificate_actual>
<pensionRegistration>true</pensionRegistration>
<governmentAnimationSearching>true</governmentAnimationSearching>
<blockedCardsStatusWay4>true</blockedCardsStatusWay4>
<autoTransfer>true</autoTransfer>
<UFSHost/>
<showUfsHistoryOperations>false</showUfsHistoryOperations>
<showSpasibo>true</showSpasibo>
<enableContactMangager>true</enableContactMangager>
<AuthCyrrilicKeypadEnabled>true</AuthCyrrilicKeypadEnabled>
<showCorporateCard>true</showCorporateCard>
<autoTouchID>true</autoTouchID>
<suggestionsEnabled>true</suggestionsEnabled>
<historyList_v2>true</historyList_v2>
<shimmersEnabled>true</shimmersEnabled>
<skeletonsEnabled>true</skeletonsEnabled>
<early2018EnterAnimation>true</early2018EnterAnimation>
<fastLoginOnMessengerPushEnabled>true</fastLoginOnMessengerPushEnabled>
<currenciesInOperationsVCEnabled>false</currenciesInOperationsVCEnabled>
<EribPenaltyDocumentsSavingAllowed>true</EribPenaltyDocumentsSavingAllowed>
<EribFinesLoadingAutoretry>true</EribFinesLoadingAutoretry>
<EribStatePaymentShortCutsEnabled>true</EribStatePaymentShortCutsEnabled>
<EribAfterPayInfoEnabled>true</EribAfterPayInfoEnabled>
<EribServicesDeeplinkEnabled>true</EribServicesDeeplinkEnabled>
<EribPenaltyInPaymentProcessEnabled>true</EribPenaltyInPaymentProcessEnabled>
<EribPenaltyDocumentsMigration>true</EribPenaltyDocumentsMigration>
<charity>
<enabled>true</enabled>
<billing>284</billing>
<provider>500437522</provider>
<service>297</service>
<text>
Здесь можно перевести любую сумму пострадавшим в Кемерове
</text>
</charity>
<overseasTransfer>true</overseasTransfer>
<importantInfoEnabled>false</importantInfoEnabled>
<historyRouterEnabled>true</historyRouterEnabled>
<SBTelecomSectionOnlyForClients>false</SBTelecomSectionOnlyForClients>
<webAnalyticsEnabled>true</webAnalyticsEnabled>
<newSectionInvestEnable>true</newSectionInvestEnable>
<newProductsVC>true</newProductsVC>
<newProductsVCv2>true</newProductsVCv2>
<hidingSectionEnabled>true</hidingSectionEnabled>
<orderingSectionEnabled>true</orderingSectionEnabled>
<hidingSectionTutorialEnabled>false</hidingSectionTutorialEnabled>
<FastLoginApp>false</FastLoginApp>
<PrintAutoSubscriptionCheck>false</PrintAutoSubscriptionCheck>
<productNavigationBarMod>3</productNavigationBarMod>
<IsFromAddrBook>true</IsFromAddrBook>
<InstantApp>true</InstantApp>
<InstantAppV2>true</InstantAppV2>
<mobilePOSEnabled>true</mobilePOSEnabled>
<earlyLoanRepayment>true</earlyLoanRepayment>
<newProductDetailsUIEnabled>true</newProductDetailsUIEnabled>
<newProductDetailsContentEnabled>true</newProductDetailsContentEnabled>
<PaymentTransactionsPopUpConfirmNumber>true</PaymentTransactionsPopUpConfirmNumber>
<soundsInAppEnabled>true</soundsInAppEnabled>
<googleMapsEnabled>false</googleMapsEnabled>
<messengerFirstLoginEnabled>false</messengerFirstLoginEnabled>
<authBlockingScreen>true</authBlockingScreen>
<PrintAutoSubscriptionTutorialCheck>true</PrintAutoSubscriptionTutorialCheck>
<balanceFromPush>true</balanceFromPush>
</node>
<node id="greenfield1.online.sberbank.ru">
<coreQR>true</coreQR>
<SBTelecom>true</SBTelecom>
<CreditRating>false</CreditRating>
<CreditRating_v2>false</CreditRating_v2>
<OKBRating>false</OKBRating>
<EnableBetaVersion>
<version>8.1.2</version>
<version>8.1.1</version>
</EnableBetaVersion>
<enableArrests>true</enableArrests>
<cardDelivery>true</cardDelivery>
<loanTable>true</loanTable>
<hideRegion>true</hideRegion>
<pciDss>true</pciDss>
<cashByCode>true</cashByCode>
<selfTransfer>true</selfTransfer>
<selfTransferP2P>true</selfTransferP2P>
<selfTransferStorno>true</selfTransferStorno>
<creditCardAutorepayment>true</creditCardAutorepayment>
<governmentServices>true</governmentServices>
<pensionTransfer>true</pensionTransfer>
<pensionCertificate>true</pensionCertificate>
<pensionRegistration>true</pensionRegistration>
<governmentServices_actual>true</governmentServices_actual>
<pensionTransfer_actual>true</pensionTransfer_actual>
<pensionCertificate_actual>true</pensionCertificate_actual>
<governmentAnimationSearching>true</governmentAnimationSearching>
<blockedCardsStatusWay4>true</blockedCardsStatusWay4>
<autoTransfer>true</autoTransfer>
<UFSHost/>
<coreCreditCardInfo_v2>true</coreCreditCardInfo_v2>
<coreCreditCardInfo_v3>true</coreCreditCardInfo_v3>
<OmniChannelHistory>true</OmniChannelHistory>
<showUfsHistoryOperations>true</showUfsHistoryOperations>
<showSpasibo>true</showSpasibo>
<enableContactMangager>true</enableContactMangager>
<AuthCyrrilicKeypadEnabled>true</AuthCyrrilicKeypadEnabled>
<showCorporateCard>true</showCorporateCard>
<autoTouchID>true</autoTouchID>
<suggestionsEnabled>true</suggestionsEnabled>
<historyList_v2>true</historyList_v2>
<shimmersEnabled>true</shimmersEnabled>
<skeletonsEnabled>true</skeletonsEnabled>
<early2018EnterAnimation>true</early2018EnterAnimation>
<fastLoginOnMessengerPushEnabled>true</fastLoginOnMessengerPushEnabled>
<currenciesInOperationsVCEnabled>false</currenciesInOperationsVCEnabled>
<EribPenaltyDocumentsSavingAllowed>true</EribPenaltyDocumentsSavingAllowed>
<EribFinesLoadingAutoretry>true</EribFinesLoadingAutoretry>
<EribStatePaymentShortCutsEnabled>true</EribStatePaymentShortCutsEnabled>
<EribAfterPayInfoEnabled>true</EribAfterPayInfoEnabled>
<EribServicesDeeplinkEnabled>true</EribServicesDeeplinkEnabled>
<EribPenaltyInPaymentProcessEnabled>true</EribPenaltyInPaymentProcessEnabled>
<EribPenaltyDocumentsMigration>true</EribPenaltyDocumentsMigration>
<charity>
<enabled>true</enabled>
<billing>284</billing>
<provider>550470225</provider>
<service>297</service>
<text>
Здесь можно перевести любую сумму пострадавшим в Кемерове
</text>
</charity>
<overseasTransfer>true</overseasTransfer>
<importantInfoEnabled>false</importantInfoEnabled>
<historyRouterEnabled>true</historyRouterEnabled>
<SBTelecomSectionOnlyForClients>false</SBTelecomSectionOnlyForClients>
<webAnalyticsEnabled>true</webAnalyticsEnabled>
<newSectionInvestEnable>true</newSectionInvestEnable>
<newProductsVC>true</newProductsVC>
<newProductsVCv2>true</newProductsVCv2>
<hidingSectionEnabled>true</hidingSectionEnabled>
<orderingSectionEnabled>true</orderingSectionEnabled>
<hidingSectionTutorialEnabled>false</hidingSectionTutorialEnabled>
<FastLoginApp>false</FastLoginApp>
<PrintAutoSubscriptionCheck>false</PrintAutoSubscriptionCheck>
<productNavigationBarMod>3</productNavigationBarMod>
<IsFromAddrBook>true</IsFromAddrBook>
<InstantApp>false</InstantApp>
<InstantAppV2>true</InstantAppV2>
<mobilePOSEnabled>true</mobilePOSEnabled>
<earlyLoanRepayment>true</earlyLoanRepayment>
<newProductDetailsUIEnabled>true</newProductDetailsUIEnabled>
<newProductDetailsContentEnabled>true</newProductDetailsContentEnabled>
<PaymentTransactionsPopUpConfirmNumber>true</PaymentTransactionsPopUpConfirmNumber>
<soundsInAppEnabled>true</soundsInAppEnabled>
<googleMapsEnabled>true</googleMapsEnabled>
<messengerFirstLoginEnabled>false</messengerFirstLoginEnabled>
<authBlockingScreen>true</authBlockingScreen>
<PrintAutoSubscriptionTutorialCheck>true</PrintAutoSubscriptionTutorialCheck>
<balanceFromPush>true</balanceFromPush>
</node>
<node id="greenfield2.online.sberbank.ru">
<coreQR>true</coreQR>
<SBTelecom>true</SBTelecom>
<CreditRating>false</CreditRating>
<CreditRating_v2>false</CreditRating_v2>
<OKBRating>false</OKBRating>
<EnableBetaVersion>
<version>8.1.2</version>
<version>8.1.1</version>
</EnableBetaVersion>
<enableArrests>true</enableArrests>
<cardDelivery>true</cardDelivery>
<loanTable>true</loanTable>
<hideRegion>true</hideRegion>
<pciDss>true</pciDss>
<cashByCode>true</cashByCode>
<selfTransfer>true</selfTransfer>
<selfTransferP2P>true</selfTransferP2P>
<selfTransferStorno>true</selfTransferStorno>
<creditCardAutorepayment>true</creditCardAutorepayment>
<governmentServices>true</governmentServices>
<pensionTransfer>true</pensionTransfer>
<pensionCertificate>true</pensionCertificate>
<governmentServices_actual>true</governmentServices_actual>
<pensionTransfer_actual>true</pensionTransfer_actual>
<pensionCertificate_actual>true</pensionCertificate_actual>
<pensionRegistration>true</pensionRegistration>
<governmentAnimationSearching>true</governmentAnimationSearching>
<blockedCardsStatusWay4>true</blockedCardsStatusWay4>
<autoTransfer>true</autoTransfer>
<UFSHost/>
<coreCreditCardInfo_v2>true</coreCreditCardInfo_v2>
<coreCreditCardInfo_v3>true</coreCreditCardInfo_v3>
<OmniChannelHistory>true</OmniChannelHistory>
<showUfsHistoryOperations>true</showUfsHistoryOperations>
<showSpasibo>true</showSpasibo>
<enableContactMangager>true</enableContactMangager>
<AuthCyrrilicKeypadEnabled>true</AuthCyrrilicKeypadEnabled>
<showCorporateCard>true</showCorporateCard>
<autoTouchID>true</autoTouchID>
<suggestionsEnabled>true</suggestionsEnabled>
<historyList_v2>true</historyList_v2>
<shimmersEnabled>true</shimmersEnabled>
<skeletonsEnabled>true</skeletonsEnabled>
<early2018EnterAnimation>true</early2018EnterAnimation>
<fastLoginOnMessengerPushEnabled>true</fastLoginOnMessengerPushEnabled>
<currenciesInOperationsVCEnabled>false</currenciesInOperationsVCEnabled>
<EribPenaltyDocumentsSavingAllowed>true</EribPenaltyDocumentsSavingAllowed>
<EribFinesLoadingAutoretry>true</EribFinesLoadingAutoretry>
<EribStatePaymentShortCutsEnabled>true</EribStatePaymentShortCutsEnabled>
<EribAfterPayInfoEnabled>true</EribAfterPayInfoEnabled>
<EribServicesDeeplinkEnabled>true</EribServicesDeeplinkEnabled>
<EribPenaltyInPaymentProcessEnabled>true</EribPenaltyInPaymentProcessEnabled>
<EribPenaltyDocumentsMigration>true</EribPenaltyDocumentsMigration>
<charity>
<enabled>true</enabled>
<billing>284</billing>
<provider>550470225</provider>
<service>297</service>
<text>
Здесь можно перевести любую сумму пострадавшим в Кемерове
</text>
</charity>
<overseasTransfer>true</overseasTransfer>
<importantInfoEnabled>false</importantInfoEnabled>
<historyRouterEnabled>true</historyRouterEnabled>
<SBTelecomSectionOnlyForClients>false</SBTelecomSectionOnlyForClients>
<webAnalyticsEnabled>true</webAnalyticsEnabled>
<newSectionInvestEnable>true</newSectionInvestEnable>
<SBMProductsViewController>true</SBMProductsViewController>
<newProductsVC>true</newProductsVC>
<newProductsVCv2>true</newProductsVCv2>
<hidingSectionEnabled>true</hidingSectionEnabled>
<orderingSectionEnabled>true</orderingSectionEnabled>
<hidingSectionTutorialEnabled>false</hidingSectionTutorialEnabled>
<FastLoginApp>false</FastLoginApp>
<PrintAutoSubscriptionCheck>false</PrintAutoSubscriptionCheck>
<productNavigationBarMod>3</productNavigationBarMod>
<IsFromAddrBook>true</IsFromAddrBook>
<InstantApp>true</InstantApp>
<InstantAppV2>true</InstantAppV2>
<mobilePOSEnabled>true</mobilePOSEnabled>
<earlyLoanRepayment>true</earlyLoanRepayment>
<newProductDetailsUIEnabled>true</newProductDetailsUIEnabled>
<newProductDetailsContentEnabled>true</newProductDetailsContentEnabled>
<PaymentTransactionsPopUpConfirmNumber>true</PaymentTransactionsPopUpConfirmNumber>
<soundsInAppEnabled>true</soundsInAppEnabled>
<googleMapsEnabled>true</googleMapsEnabled>
<messengerFirstLoginEnabled>false</messengerFirstLoginEnabled>
<authBlockingScreen>true</authBlockingScreen>
<PrintAutoSubscriptionTutorialCheck>true</PrintAutoSubscriptionTutorialCheck>
<balanceFromPush>true</balanceFromPush>
</node>
<node id="mobile.sberbank.ru">
<coreQR>true</coreQR>
<SBTelecom>true</SBTelecom>
<CreditRating>false</CreditRating>
<CreditRating_v2>false</CreditRating_v2>
<OKBRating>true</OKBRating>
<EnableBetaVersion>
<version>8.1.2</version>
<version>8.1.1</version>
</EnableBetaVersion>
<enableArrests>true</enableArrests>
<cardDelivery>true</cardDelivery>
<loanTable>true</loanTable>
<hideRegion>true</hideRegion>
<pciDss>true</pciDss>
<cashByCode>true</cashByCode>
<selfTransfer>true</selfTransfer>
<selfTransferP2P>true</selfTransferP2P>
<selfTransferStorno>true</selfTransferStorno>
<creditCardAutorepayment>true</creditCardAutorepayment>
<governmentServices>true</governmentServices>
<pensionTransfer>true</pensionTransfer>
<pensionCertificate>true</pensionCertificate>
<governmentServices_actual>true</governmentServices_actual>
<pensionTransfer_actual>true</pensionTransfer_actual>
<pensionCertificate_actual>true</pensionCertificate_actual>
<pensionRegistration>true</pensionRegistration>
<governmentAnimationSearching>true</governmentAnimationSearching>
<blockedCardsStatusWay4>true</blockedCardsStatusWay4>
<autoTransfer>true</autoTransfer>
<UFSHost>pfl-psi.efstst.sigma.sbrf.ru:443</UFSHost>
<coreCreditCardInfo_v2>true</coreCreditCardInfo_v2>
<coreCreditCardInfo_v3>true</coreCreditCardInfo_v3>
<OmniChannelHistory>true</OmniChannelHistory>
<showUfsHistoryOperations>true</showUfsHistoryOperations>
<showSpasibo>true</showSpasibo>
<enableContactMangager>true</enableContactMangager>
<AuthCyrrilicKeypadEnabled>true</AuthCyrrilicKeypadEnabled>
<showCorporateCard>true</showCorporateCard>
<autoTouchID>true</autoTouchID>
<suggestionsEnabled>true</suggestionsEnabled>
<historyList_v2>true</historyList_v2>
<shimmersEnabled>true</shimmersEnabled>
<skeletonsEnabled>true</skeletonsEnabled>
<early2018EnterAnimation>true</early2018EnterAnimation>
<fastLoginOnMessengerPushEnabled>true</fastLoginOnMessengerPushEnabled>
<currenciesInOperationsVCEnabled>false</currenciesInOperationsVCEnabled>
<EribPenaltyDocumentsSavingAllowed>true</EribPenaltyDocumentsSavingAllowed>
<EribFinesLoadingAutoretry>true</EribFinesLoadingAutoretry>
<EribStatePaymentShortCutsEnabled>true</EribStatePaymentShortCutsEnabled>
<EribAfterPayInfoEnabled>true</EribAfterPayInfoEnabled>
<EribServicesDeeplinkEnabled>true</EribServicesDeeplinkEnabled>
<EribPenaltyInPaymentProcessEnabled>true</EribPenaltyInPaymentProcessEnabled>
<EribPenaltyDocumentsMigration>true</EribPenaltyDocumentsMigration>
<charity>
<enabled>true</enabled>
<billing>4</billing>
<provider>3</provider>
<service>3</service>
<text>
Здесь можно перевести любую сумму пострадавшим в Кемерове
</text>
</charity>
<overseasTransfer>true</overseasTransfer>
<importantInfoEnabled>false</importantInfoEnabled>
<historyRouterEnabled>true</historyRouterEnabled>
<SBTelecomSectionOnlyForClients>false</SBTelecomSectionOnlyForClients>
<webAnalyticsEnabled>true</webAnalyticsEnabled>
<newSectionInvestEnable>true</newSectionInvestEnable>
<newProductsVC>true</newProductsVC>
<newProductsVCv2>true</newProductsVCv2>
<hidingSectionEnabled>true</hidingSectionEnabled>
<orderingSectionEnabled>true</orderingSectionEnabled>
<hidingSectionTutorialEnabled>false</hidingSectionTutorialEnabled>
<arrestInfoService>true</arrestInfoService>
<FastLoginApp>false</FastLoginApp>
<PrintAutoSubscriptionCheck>true</PrintAutoSubscriptionCheck>
<productNavigationBarMod>3</productNavigationBarMod>
<IsFromAddrBook>true</IsFromAddrBook>
<InstantApp>true</InstantApp>
<InstantAppV2>true</InstantAppV2>
<mobilePOSEnabled>true</mobilePOSEnabled>
<earlyLoanRepayment>true</earlyLoanRepayment>
<newProductDetailsUIEnabled>true</newProductDetailsUIEnabled>
<newProductDetailsContentEnabled>true</newProductDetailsContentEnabled>
<soundsInAppEnabled>true</soundsInAppEnabled>
<PaymentTransactionsPopUpConfirmNumber>true</PaymentTransactionsPopUpConfirmNumber>
<googleMapsEnabled>false</googleMapsEnabled>
<messengerFirstLoginEnabled>false</messengerFirstLoginEnabled>
<authBlockingScreen>true</authBlockingScreen>
<PrintAutoSubscriptionTutorialCheck>true</PrintAutoSubscriptionTutorialCheck>
<balanceFromPush>true</balanceFromPush>
</node>
<node id="ift-node1.testonline.sberbank.ru">
<coreQR>true</coreQR>
<SBTelecom>true</SBTelecom>
<CreditRating>false</CreditRating>
<CreditRating_v2>false</CreditRating_v2>
<OKBRating>true</OKBRating>
<EnableBetaVersion>
<version>8.1.2</version>
<version>8.1.1</version>
</EnableBetaVersion>
<enableArrests>true</enableArrests>
<cardDelivery>true</cardDelivery>
<loanTable>true</loanTable>
<hideRegion>true</hideRegion>
<pciDss>true</pciDss>
<cashByCode>true</cashByCode>
<selfTransfer>true</selfTransfer>
<selfTransferP2P>true</selfTransferP2P>
<selfTransferStorno>true</selfTransferStorno>
<creditCardAutorepayment>true</creditCardAutorepayment>
<governmentServices>true</governmentServices>
<pensionTransfer>true</pensionTransfer>
<pensionCertificate>true</pensionCertificate>
<governmentServices_actual>true</governmentServices_actual>
<pensionTransfer_actual>true</pensionTransfer_actual>
<pensionCertificate_actual>true</pensionCertificate_actual>
<pensionRegistration>true</pensionRegistration>
<governmentAnimationSearching>true</governmentAnimationSearching>
<blockedCardsStatusWay4>true</blockedCardsStatusWay4>
<autoTransfer>true</autoTransfer>
<UFSHost>ift.testefs.sberbank.ru:443</UFSHost>
<coreCreditCardInfo_v2>true</coreCreditCardInfo_v2>
<coreCreditCardInfo_v3>true</coreCreditCardInfo_v3>
<OmniChannelHistory>true</OmniChannelHistory>
<showUfsHistoryOperations>true</showUfsHistoryOperations>
<showSpasibo>true</showSpasibo>
<enableContactMangager>true</enableContactMangager>
<AuthCyrrilicKeypadEnabled>true</AuthCyrrilicKeypadEnabled>
<showCorporateCard>true</showCorporateCard>
<autoTouchID>true</autoTouchID>
<suggestionsEnabled>true</suggestionsEnabled>
<historyList_v2>true</historyList_v2>
<shimmersEnabled>true</shimmersEnabled>
<skeletonsEnabled>true</skeletonsEnabled>
<early2018EnterAnimation>true</early2018EnterAnimation>
<fastLoginOnMessengerPushEnabled>true</fastLoginOnMessengerPushEnabled>
<currenciesInOperationsVCEnabled>false</currenciesInOperationsVCEnabled>
<EribPenaltyDocumentsSavingAllowed>true</EribPenaltyDocumentsSavingAllowed>
<EribFinesLoadingAutoretry>true</EribFinesLoadingAutoretry>
<EribStatePaymentShortCutsEnabled>true</EribStatePaymentShortCutsEnabled>
<EribAfterPayInfoEnabled>true</EribAfterPayInfoEnabled>
<EribServicesDeeplinkEnabled>true</EribServicesDeeplinkEnabled>
<EribPenaltyInPaymentProcessEnabled>true</EribPenaltyInPaymentProcessEnabled>
<EribPenaltyDocumentsMigration>true</EribPenaltyDocumentsMigration>
<overseasTransfer>true</overseasTransfer>
<importantInfoEnabled>false</importantInfoEnabled>
<historyRouterEnabled>true</historyRouterEnabled>
<SBTelecomSectionOnlyForClients>false</SBTelecomSectionOnlyForClients>
<webAnalyticsEnabled>true</webAnalyticsEnabled>
<newSectionInvestEnable>true</newSectionInvestEnable>
<newProductsVC>true</newProductsVC>
<newProductsVCv2>true</newProductsVCv2>
<hidingSectionEnabled>true</hidingSectionEnabled>
<orderingSectionEnabled>true</orderingSectionEnabled>
<hidingSectionTutorialEnabled>false</hidingSectionTutorialEnabled>
<arrestInfoService>true</arrestInfoService>
<FastLoginApp>false</FastLoginApp>
<PrintAutoSubscriptionCheck>true</PrintAutoSubscriptionCheck>
<productNavigationBarMod>3</productNavigationBarMod>
<IsFromAddrBook>true</IsFromAddrBook>
<InstantApp>true</InstantApp>
<InstantAppV2>true</InstantAppV2>
<mobilePOSEnabled>true</mobilePOSEnabled>
<earlyLoanRepayment>true</earlyLoanRepayment>
<newProductDetailsUIEnabled>true</newProductDetailsUIEnabled>
<newProductDetailsContentEnabled>true</newProductDetailsContentEnabled>
<PaymentTransactionsPopUpConfirmNumber>true</PaymentTransactionsPopUpConfirmNumber>
<soundsInAppEnabled>true</soundsInAppEnabled>
<googleMapsEnabled>true</googleMapsEnabled>
<messengerFirstLoginEnabled>false</messengerFirstLoginEnabled>
<authBlockingScreen>false</authBlockingScreen>
<PrintAutoSubscriptionTutorialCheck>true</PrintAutoSubscriptionTutorialCheck>
<balanceFromPush>true</balanceFromPush>
</node>
<node id="ift-node2.testonline.sberbank.ru">
<coreQR>true</coreQR>
<SBTelecom>true</SBTelecom>
<CreditRating>false</CreditRating>
<CreditRating_v2>false</CreditRating_v2>
<OKBRating>true</OKBRating>
<EnableBetaVersion>
<version>8.1.2</version>
<version>8.1.1</version>
</EnableBetaVersion>
<enableArrests>true</enableArrests>
<cardDelivery>true</cardDelivery>
<loanTable>true</loanTable>
<hideRegion>true</hideRegion>
<pciDss>true</pciDss>
<cashByCode>true</cashByCode>
<selfTransfer>true</selfTransfer>
<selfTransferP2P>true</selfTransferP2P>
<selfTransferStorno>true</selfTransferStorno>
<creditCardAutorepayment>true</creditCardAutorepayment>
<governmentServices>true</governmentServices>
<pensionTransfer>true</pensionTransfer>
<pensionCertificate>true</pensionCertificate>
<governmentServices_actual>true</governmentServices_actual>
<pensionTransfer_actual>true</pensionTransfer_actual>
<pensionCertificate_actual>true</pensionCertificate_actual>
<pensionRegistration>true</pensionRegistration>
<governmentAnimationSearching>true</governmentAnimationSearching>
<blockedCardsStatusWay4>true</blockedCardsStatusWay4>
<autoTransfer>true</autoTransfer>
<UFSHost>ift.testefs.sberbank.ru:443</UFSHost>
<coreCreditCardInfo_v2>true</coreCreditCardInfo_v2>
<coreCreditCardInfo_v3>true</coreCreditCardInfo_v3>
<OmniChannelHistory>true</OmniChannelHistory>
<showUfsHistoryOperations>true</showUfsHistoryOperations>
<showSpasibo>true</showSpasibo>
<enableContactMangager>true</enableContactMangager>
<AuthCyrrilicKeypadEnabled>true</AuthCyrrilicKeypadEnabled>
<showCorporateCard>true</showCorporateCard>
<autoTouchID>true</autoTouchID>
<suggestionsEnabled>true</suggestionsEnabled>
<historyList_v2>true</historyList_v2>
<shimmersEnabled>true</shimmersEnabled>
<skeletonsEnabled>true</skeletonsEnabled>
<early2018EnterAnimation>true</early2018EnterAnimation>
<fastLoginOnMessengerPushEnabled>true</fastLoginOnMessengerPushEnabled>
<currenciesInOperationsVCEnabled>false</currenciesInOperationsVCEnabled>
<EribPenaltyDocumentsSavingAllowed>true</EribPenaltyDocumentsSavingAllowed>
<EribFinesLoadingAutoretry>true</EribFinesLoadingAutoretry>
<EribStatePaymentShortCutsEnabled>true</EribStatePaymentShortCutsEnabled>
<EribAfterPayInfoEnabled>true</EribAfterPayInfoEnabled>
<EribServicesDeeplinkEnabled>true</EribServicesDeeplinkEnabled>
<EribPenaltyInPaymentProcessEnabled>true</EribPenaltyInPaymentProcessEnabled>
<EribPenaltyDocumentsMigration>true</EribPenaltyDocumentsMigration>
<overseasTransfer>true</overseasTransfer>
<importantInfoEnabled>false</importantInfoEnabled>
<historyRouterEnabled>true</historyRouterEnabled>
<SBTelecomSectionOnlyForClients>false</SBTelecomSectionOnlyForClients>
<webAnalyticsEnabled>true</webAnalyticsEnabled>
<newSectionInvestEnable>true</newSectionInvestEnable>
<newProductsVC>true</newProductsVC>
<newProductsVCv2>true</newProductsVCv2>
<hidingSectionEnabled>true</hidingSectionEnabled>
<orderingSectionEnabled>true</orderingSectionEnabled>
<hidingSectionTutorialEnabled>false</hidingSectionTutorialEnabled>
<arrestInfoService>true</arrestInfoService>
<FastLoginApp>false</FastLoginApp>
<PrintAutoSubscriptionCheck>true</PrintAutoSubscriptionCheck>
<productNavigationBarMod>3</productNavigationBarMod>
<IsFromAddrBook>true</IsFromAddrBook>
<InstantApp>true</InstantApp>
<InstantAppV2>true</InstantAppV2>
<mobilePOSEnabled>true</mobilePOSEnabled>
<earlyLoanRepayment>true</earlyLoanRepayment>
<newProductDetailsUIEnabled>true</newProductDetailsUIEnabled>
<newProductDetailsContentEnabled>true</newProductDetailsContentEnabled>
<PaymentTransactionsPopUpConfirmNumber>true</PaymentTransactionsPopUpConfirmNumber>
<soundsInAppEnabled>true</soundsInAppEnabled>
<googleMapsEnabled>true</googleMapsEnabled>
<messengerFirstLoginEnabled>false</messengerFirstLoginEnabled>
<authBlockingScreen>false</authBlockingScreen>
<PrintAutoSubscriptionTutorialCheck>true</PrintAutoSubscriptionTutorialCheck>
<balanceFromPush>true</balanceFromPush>
</node>
<node id="ift-node5.testonline.sberbank.ru">
<coreQR>true</coreQR>
<SBTelecom>true</SBTelecom>
<CreditRating>false</CreditRating>
<CreditRating_v2>false</CreditRating_v2>
<OKBRating>true</OKBRating>
<EnableBetaVersion>
<version>8.1.2</version>
<version>8.1.1</version>
</EnableBetaVersion>
<enableArrests>true</enableArrests>
<cardDelivery>true</cardDelivery>
<loanTable>true</loanTable>
<hideRegion>true</hideRegion>
<pciDss>true</pciDss>
<cashByCode>true</cashByCode>
<selfTransfer>true</selfTransfer>
<selfTransferP2P>true</selfTransferP2P>
<selfTransferStorno>true</selfTransferStorno>
<creditCardAutorepayment>true</creditCardAutorepayment>
<governmentServices>true</governmentServices>
<pensionTransfer>true</pensionTransfer>
<pensionCertificate>true</pensionCertificate>
<governmentServices_actual>true</governmentServices_actual>
<pensionTransfer_actual>true</pensionTransfer_actual>
<pensionCertificate_actual>true</pensionCertificate_actual>
<pensionRegistration>true</pensionRegistration>
<governmentAnimationSearching>true</governmentAnimationSearching>
<blockedCardsStatusWay4>true</blockedCardsStatusWay4>
<autoTransfer>true</autoTransfer>
<UFSHost>ift.testefs.sberbank.ru:443</UFSHost>
<coreCreditCardInfo_v2>true</coreCreditCardInfo_v2>
<coreCreditCardInfo_v3>true</coreCreditCardInfo_v3>
<OmniChannelHistory>true</OmniChannelHistory>
<showUfsHistoryOperations>true</showUfsHistoryOperations>
<showSpasibo>true</showSpasibo>
<enableContactMangager>true</enableContactMangager>
<AuthCyrrilicKeypadEnabled>true</AuthCyrrilicKeypadEnabled>
<showCorporateCard>true</showCorporateCard>
<autoTouchID>true</autoTouchID>
<suggestionsEnabled>true</suggestionsEnabled>
<historyList_v2>true</historyList_v2>
<shimmersEnabled>true</shimmersEnabled>
<skeletonsEnabled>true</skeletonsEnabled>
<early2018EnterAnimation>true</early2018EnterAnimation>
<fastLoginOnMessengerPushEnabled>true</fastLoginOnMessengerPushEnabled>
<currenciesInOperationsVCEnabled>false</currenciesInOperationsVCEnabled>
<EribPenaltyDocumentsSavingAllowed>true</EribPenaltyDocumentsSavingAllowed>
<EribFinesLoadingAutoretry>true</EribFinesLoadingAutoretry>
<EribStatePaymentShortCutsEnabled>true</EribStatePaymentShortCutsEnabled>
<EribAfterPayInfoEnabled>true</EribAfterPayInfoEnabled>
<EribServicesDeeplinkEnabled>true</EribServicesDeeplinkEnabled>
<EribPenaltyInPaymentProcessEnabled>true</EribPenaltyInPaymentProcessEnabled>
<EribPenaltyDocumentsMigration>true</EribPenaltyDocumentsMigration>
<overseasTransfer>true</overseasTransfer>
<importantInfoEnabled>false</importantInfoEnabled>
<historyRouterEnabled>true</historyRouterEnabled>
<SBTelecomSectionOnlyForClients>false</SBTelecomSectionOnlyForClients>
<webAnalyticsEnabled>true</webAnalyticsEnabled>
<newSectionInvestEnable>true</newSectionInvestEnable>
<newProductsVC>true</newProductsVC>
<newProductsVCv2>true</newProductsVCv2>
<hidingSectionEnabled>true</hidingSectionEnabled>
<orderingSectionEnabled>true</orderingSectionEnabled>
<hidingSectionTutorialEnabled>false</hidingSectionTutorialEnabled>
<arrestInfoService>true</arrestInfoService>
<FastLoginApp>false</FastLoginApp>
<PrintAutoSubscriptionCheck>true</PrintAutoSubscriptionCheck>
<productNavigationBarMod>3</productNavigationBarMod>
<IsFromAddrBook>true</IsFromAddrBook>
<InstantApp>true</InstantApp>
<InstantAppV2>true</InstantAppV2>
<mobilePOSEnabled>true</mobilePOSEnabled>
<earlyLoanRepayment>true</earlyLoanRepayment>
<newProductDetailsUIEnabled>true</newProductDetailsUIEnabled>
<newProductDetailsContentEnabled>true</newProductDetailsContentEnabled>
<PaymentTransactionsPopUpConfirmNumber>true</PaymentTransactionsPopUpConfirmNumber>
<soundsInAppEnabled>true</soundsInAppEnabled>
<googleMapsEnabled>false</googleMapsEnabled>
<messengerFirstLoginEnabled>false</messengerFirstLoginEnabled>
<authBlockingScreen>true</authBlockingScreen>
<PrintAutoSubscriptionTutorialCheck>true</PrintAutoSubscriptionTutorialCheck>
<balanceFromPush>true</balanceFromPush>
</node>
<node id="ift-node1-mp.testonline.sberbank.ru">
<coreQR>true</coreQR>
<SBTelecom>true</SBTelecom>
<CreditRating>false</CreditRating>
<CreditRating_v2>false</CreditRating_v2>
<OKBRating>true</OKBRating>
<EnableBetaVersion>
<version>8.1.2</version>
<version>8.1.1</version>
</EnableBetaVersion>
<enableArrests>true</enableArrests>
<cardDelivery>true</cardDelivery>
<loanTable>true</loanTable>
<hideRegion>true</hideRegion>
<pciDss>true</pciDss>
<cashByCode>true</cashByCode>
<selfTransfer>true</selfTransfer>
<selfTransferP2P>true</selfTransferP2P>
<selfTransferStorno>true</selfTransferStorno>
<creditCardAutorepayment>true</creditCardAutorepayment>
<governmentServices>true</governmentServices>
<pensionTransfer>true</pensionTransfer>
<pensionCertificate>true</pensionCertificate>
<governmentServices_actual>true</governmentServices_actual>
<pensionTransfer_actual>true</pensionTransfer_actual>
<pensionCertificate_actual>true</pensionCertificate_actual>
<pensionRegistration>true</pensionRegistration>
<governmentAnimationSearching>true</governmentAnimationSearching>
<blockedCardsStatusWay4>true</blockedCardsStatusWay4>
<autoTransfer>true</autoTransfer>
<UFSHost>ift.testefs.sberbank.ru:443</UFSHost>
<coreCreditCardInfo_v2>true</coreCreditCardInfo_v2>
<coreCreditCardInfo_v3>true</coreCreditCardInfo_v3>
<OmniChannelHistory>true</OmniChannelHistory>
<showUfsHistoryOperations>true</showUfsHistoryOperations>
<showSpasibo>true</showSpasibo>
<enableContactMangager>true</enableContactMangager>
<AuthCyrrilicKeypadEnabled>true</AuthCyrrilicKeypadEnabled>
<showCorporateCard>true</showCorporateCard>
<autoTouchID>true</autoTouchID>
<suggestionsEnabled>true</suggestionsEnabled>
<historyList_v2>true</historyList_v2>
<shimmersEnabled>true</shimmersEnabled>
<skeletonsEnabled>true</skeletonsEnabled>
<early2018EnterAnimation>true</early2018EnterAnimation>
<fastLoginOnMessengerPushEnabled>true</fastLoginOnMessengerPushEnabled>
<currenciesInOperationsVCEnabled>false</currenciesInOperationsVCEnabled>
<EribPenaltyDocumentsSavingAllowed>true</EribPenaltyDocumentsSavingAllowed>
<EribFinesLoadingAutoretry>true</EribFinesLoadingAutoretry>
<EribStatePaymentShortCutsEnabled>true</EribStatePaymentShortCutsEnabled>
<EribAfterPayInfoEnabled>true</EribAfterPayInfoEnabled>
<EribServicesDeeplinkEnabled>true</EribServicesDeeplinkEnabled>
<EribPenaltyInPaymentProcessEnabled>true</EribPenaltyInPaymentProcessEnabled>
<EribPenaltyDocumentsMigration>true</EribPenaltyDocumentsMigration>
<overseasTransfer>true</overseasTransfer>
<importantInfoEnabled>false</importantInfoEnabled>
<historyRouterEnabled>true</historyRouterEnabled>
<SBTelecomSectionOnlyForClients>false</SBTelecomSectionOnlyForClients>
<webAnalyticsEnabled>true</webAnalyticsEnabled>
<newSectionInvestEnable>true</newSectionInvestEnable>
<newProductsVC>true</newProductsVC>
<newProductsVCv2>true</newProductsVCv2>
<hidingSectionEnabled>true</hidingSectionEnabled>
<orderingSectionEnabled>true</orderingSectionEnabled>
<hidingSectionTutorialEnabled>false</hidingSectionTutorialEnabled>
<arrestInfoService>true</arrestInfoService>
<FastLoginApp>false</FastLoginApp>
<PrintAutoSubscriptionCheck>true</PrintAutoSubscriptionCheck>
<productNavigationBarMod>3</productNavigationBarMod>
<IsFromAddrBook>true</IsFromAddrBook>
<InstantApp>true</InstantApp>
<InstantAppV2>true</InstantAppV2>
<mobilePOSEnabled>true</mobilePOSEnabled>
<earlyLoanRepayment>true</earlyLoanRepayment>
<newProductDetailsUIEnabled>true</newProductDetailsUIEnabled>
<newProductDetailsContentEnabled>true</newProductDetailsContentEnabled>
<PaymentTransactionsPopUpConfirmNumber>true</PaymentTransactionsPopUpConfirmNumber>
<soundsInAppEnabled>true</soundsInAppEnabled>
<messengerFirstLoginEnabled>false</messengerFirstLoginEnabled>
<authBlockingScreen>false</authBlockingScreen>
<PrintAutoSubscriptionTutorialCheck>true</PrintAutoSubscriptionTutorialCheck>
<balanceFromPush>true</balanceFromPush>
</node>
<node id="ift-node0-mp.testonline.sberbank.ru">
<coreQR>true</coreQR>
<SBTelecom>true</SBTelecom>
<CreditRating>false</CreditRating>
<CreditRating_v2>false</CreditRating_v2>
<OKBRating>true</OKBRating>
<EnableBetaVersion>
<version>8.1.2</version>
<version>8.1.1</version>
</EnableBetaVersion>
<enableArrests>true</enableArrests>
<cardDelivery>true</cardDelivery>
<loanTable>true</loanTable>
<hideRegion>true</hideRegion>
<pciDss>true</pciDss>
<cashByCode>true</cashByCode>
<selfTransfer>true</selfTransfer>
<selfTransferP2P>true</selfTransferP2P>
<selfTransferStorno>true</selfTransferStorno>
<creditCardAutorepayment>true</creditCardAutorepayment>
<governmentServices>true</governmentServices>
<pensionTransfer>true</pensionTransfer>
<pensionCertificate>true</pensionCertificate>
<governmentServices_actual>true</governmentServices_actual>
<pensionTransfer_actual>true</pensionTransfer_actual>
<pensionCertificate_actual>true</pensionCertificate_actual>
<pensionRegistration>true</pensionRegistration>
<governmentAnimationSearching>true</governmentAnimationSearching>
<blockedCardsStatusWay4>true</blockedCardsStatusWay4>
<autoTransfer>true</autoTransfer>
<UFSHost>ift.testefs.sberbank.ru:443</UFSHost>
<coreCreditCardInfo_v2>true</coreCreditCardInfo_v2>
<coreCreditCardInfo_v3>true</coreCreditCardInfo_v3>
<OmniChannelHistory>true</OmniChannelHistory>
<showUfsHistoryOperations>true</showUfsHistoryOperations>
<showSpasibo>true</showSpasibo>
<enableContactMangager>true</enableContactMangager>
<AuthCyrrilicKeypadEnabled>true</AuthCyrrilicKeypadEnabled>
<showCorporateCard>true</showCorporateCard>
<autoTouchID>true</autoTouchID>
<suggestionsEnabled>true</suggestionsEnabled>
<historyList_v2>true</historyList_v2>
<shimmersEnabled>true</shimmersEnabled>
<skeletonsEnabled>true</skeletonsEnabled>
<early2018EnterAnimation>true</early2018EnterAnimation>
<fastLoginOnMessengerPushEnabled>true</fastLoginOnMessengerPushEnabled>
<currenciesInOperationsVCEnabled>false</currenciesInOperationsVCEnabled>
<EribPenaltyDocumentsSavingAllowed>true</EribPenaltyDocumentsSavingAllowed>
<EribFinesLoadingAutoretry>true</EribFinesLoadingAutoretry>
<EribStatePaymentShortCutsEnabled>true</EribStatePaymentShortCutsEnabled>
<EribAfterPayInfoEnabled>true</EribAfterPayInfoEnabled>
<EribServicesDeeplinkEnabled>true</EribServicesDeeplinkEnabled>
<EribPenaltyInPaymentProcessEnabled>true</EribPenaltyInPaymentProcessEnabled>
<EribPenaltyDocumentsMigration>true</EribPenaltyDocumentsMigration>
<overseasTransfer>true</overseasTransfer>
<importantInfoEnabled>false</importantInfoEnabled>
<historyRouterEnabled>true</historyRouterEnabled>
<SBTelecomSectionOnlyForClients>false</SBTelecomSectionOnlyForClients>
<webAnalyticsEnabled>true</webAnalyticsEnabled>
<newSectionInvestEnable>true</newSectionInvestEnable>
<newProductsVC>true</newProductsVC>
<newProductsVCv2>true</newProductsVCv2>
<hidingSectionEnabled>true</hidingSectionEnabled>
<orderingSectionEnabled>true</orderingSectionEnabled>
<hidingSectionTutorialEnabled>false</hidingSectionTutorialEnabled>
<arrestInfoService>true</arrestInfoService>
<FastLoginApp>false</FastLoginApp>
<PrintAutoSubscriptionCheck>true</PrintAutoSubscriptionCheck>
<productNavigationBarMod>3</productNavigationBarMod>
<IsFromAddrBook>true</IsFromAddrBook>
<InstantApp>true</InstantApp>
<InstantAppV2>true</InstantAppV2>
<mobilePOSEnabled>true</mobilePOSEnabled>
<earlyLoanRepayment>true</earlyLoanRepayment>
<newProductDetailsUIEnabled>true</newProductDetailsUIEnabled>
<newProductDetailsContentEnabled>true</newProductDetailsContentEnabled>
<PaymentTransactionsPopUpConfirmNumber>true</PaymentTransactionsPopUpConfirmNumber>
<soundsInAppEnabled>true</soundsInAppEnabled>
<messengerFirstLoginEnabled>false</messengerFirstLoginEnabled>
<authBlockingScreen>false</authBlockingScreen>
<PrintAutoSubscriptionTutorialCheck>true</PrintAutoSubscriptionTutorialCheck>
<balanceFromPush>true</balanceFromPush>
</node>
<node id="ift-node2-mp.testonline.sberbank.ru">
<coreQR>true</coreQR>
<SBTelecom>true</SBTelecom>
<CreditRating>false</CreditRating>
<CreditRating_v2>false</CreditRating_v2>
<OKBRating>true</OKBRating>
<EnableBetaVersion>
<version>8.1.2</version>
<version>8.1.1</version>
</EnableBetaVersion>
<enableArrests>true</enableArrests>
<cardDelivery>true</cardDelivery>
<loanTable>true</loanTable>
<hideRegion>true</hideRegion>
<pciDss>true</pciDss>
<cashByCode>true</cashByCode>
<selfTransfer>true</selfTransfer>
<selfTransferP2P>true</selfTransferP2P>
<selfTransferStorno>true</selfTransferStorno>
<creditCardAutorepayment>true</creditCardAutorepayment>
<governmentServices>true</governmentServices>
<pensionTransfer>true</pensionTransfer>
<pensionCertificate>true</pensionCertificate>
<governmentServices_actual>true</governmentServices_actual>
<pensionTransfer_actual>true</pensionTransfer_actual>
<pensionCertificate_actual>true</pensionCertificate_actual>
<pensionRegistration>true</pensionRegistration>
<governmentAnimationSearching>true</governmentAnimationSearching>
<blockedCardsStatusWay4>true</blockedCardsStatusWay4>
<autoTransfer>true</autoTransfer>
<UFSHost>ift.testefs.sberbank.ru:443</UFSHost>
<coreCreditCardInfo_v2>true</coreCreditCardInfo_v2>
<coreCreditCardInfo_v3>true</coreCreditCardInfo_v3>
<OmniChannelHistory>true</OmniChannelHistory>
<showUfsHistoryOperations>true</showUfsHistoryOperations>
<showSpasibo>true</showSpasibo>
<enableContactMangager>true</enableContactMangager>
<AuthCyrrilicKeypadEnabled>true</AuthCyrrilicKeypadEnabled>
<showCorporateCard>true</showCorporateCard>
<autoTouchID>true</autoTouchID>
<suggestionsEnabled>true</suggestionsEnabled>
<historyList_v2>true</historyList_v2>
<shimmersEnabled>true</shimmersEnabled>
<skeletonsEnabled>true</skeletonsEnabled>
<early2018EnterAnimation>true</early2018EnterAnimation>
<fastLoginOnMessengerPushEnabled>true</fastLoginOnMessengerPushEnabled>
<currenciesInOperationsVCEnabled>false</currenciesInOperationsVCEnabled>
<EribPenaltyDocumentsSavingAllowed>true</EribPenaltyDocumentsSavingAllowed>
<EribFinesLoadingAutoretry>true</EribFinesLoadingAutoretry>
<EribStatePaymentShortCutsEnabled>true</EribStatePaymentShortCutsEnabled>
<EribAfterPayInfoEnabled>true</EribAfterPayInfoEnabled>
<EribServicesDeeplinkEnabled>true</EribServicesDeeplinkEnabled>
<EribPenaltyInPaymentProcessEnabled>true</EribPenaltyInPaymentProcessEnabled>
<EribPenaltyDocumentsMigration>true</EribPenaltyDocumentsMigration>
<overseasTransfer>true</overseasTransfer>
<importantInfoEnabled>false</importantInfoEnabled>
<historyRouterEnabled>true</historyRouterEnabled>
<SBTelecomSectionOnlyForClients>false</SBTelecomSectionOnlyForClients>
<webAnalyticsEnabled>true</webAnalyticsEnabled>
<newSectionInvestEnable>true</newSectionInvestEnable>
<newProductsVC>true</newProductsVC>
<newProductsVCv2>true</newProductsVCv2>
<hidingSectionEnabled>true</hidingSectionEnabled>
<orderingSectionEnabled>true</orderingSectionEnabled>
<hidingSectionTutorialEnabled>false</hidingSectionTutorialEnabled>
<arrestInfoService>true</arrestInfoService>
<FastLoginApp>false</FastLoginApp>
<PrintAutoSubscriptionCheck>true</PrintAutoSubscriptionCheck>
<productNavigationBarMod>3</productNavigationBarMod>
<IsFromAddrBook>true</IsFromAddrBook>
<InstantApp>true</InstantApp>
<InstantAppV2>true</InstantAppV2>
<mobilePOSEnabled>true</mobilePOSEnabled>
<earlyLoanRepayment>true</earlyLoanRepayment>
<newProductDetailsUIEnabled>true</newProductDetailsUIEnabled>
<newProductDetailsContentEnabled>true</newProductDetailsContentEnabled>
<PaymentTransactionsPopUpConfirmNumber>true</PaymentTransactionsPopUpConfirmNumber>
<soundsInAppEnabled>true</soundsInAppEnabled>
<googleMapsEnabled>true</googleMapsEnabled>
<messengerFirstLoginEnabled>false</messengerFirstLoginEnabled>
<authBlockingScreen>true</authBlockingScreen>
<PrintAutoSubscriptionTutorialCheck>true</PrintAutoSubscriptionTutorialCheck>
<balanceFromPush>true</balanceFromPush>
</node>
<node id="ift-node5-mp.testonline.sberbank.ru">
<coreQR>true</coreQR>
<SBTelecom>true</SBTelecom>
<CreditRating>false</CreditRating>
<CreditRating_v2>false</CreditRating_v2>
<OKBRating>true</OKBRating>
<EnableBetaVersion>
<version>8.1.2</version>
<version>8.1.1</version>
</EnableBetaVersion>
<enableArrests>true</enableArrests>
<cardDelivery>true</cardDelivery>
<loanTable>true</loanTable>
<hideRegion>true</hideRegion>
<pciDss>true</pciDss>
<cashByCode>true</cashByCode>
<selfTransfer>true</selfTransfer>
<selfTransferP2P>true</selfTransferP2P>
<selfTransferStorno>true</selfTransferStorno>
<creditCardAutorepayment>true</creditCardAutorepayment>
<governmentServices>true</governmentServices>
<pensionTransfer>true</pensionTransfer>
<pensionCertificate>true</pensionCertificate>
<governmentServices_actual>true</governmentServices_actual>
<pensionTransfer_actual>true</pensionTransfer_actual>
<pensionCertificate_actual>true</pensionCertificate_actual>
<pensionRegistration>true</pensionRegistration>
<governmentAnimationSearching>true</governmentAnimationSearching>
<blockedCardsStatusWay4>true</blockedCardsStatusWay4>
<autoTransfer>true</autoTransfer>
<UFSHost>ift.testefs.sberbank.ru:443</UFSHost>
<coreCreditCardInfo_v2>true</coreCreditCardInfo_v2>
<coreCreditCardInfo_v3>true</coreCreditCardInfo_v3>
<OmniChannelHistory>true</OmniChannelHistory>
<showUfsHistoryOperations>true</showUfsHistoryOperations>
<showSpasibo>true</showSpasibo>
<enableContactMangager>true</enableContactMangager>
<AuthCyrrilicKeypadEnabled>true</AuthCyrrilicKeypadEnabled>
<showCorporateCard>true</showCorporateCard>
<autoTouchID>true</autoTouchID>
<suggestionsEnabled>true</suggestionsEnabled>
<historyList_v2>true</historyList_v2>
<shimmersEnabled>true</shimmersEnabled>
<skeletonsEnabled>true</skeletonsEnabled>
<early2018EnterAnimation>true</early2018EnterAnimation>
<fastLoginOnMessengerPushEnabled>true</fastLoginOnMessengerPushEnabled>
<currenciesInOperationsVCEnabled>false</currenciesInOperationsVCEnabled>
<EribPenaltyDocumentsSavingAllowed>true</EribPenaltyDocumentsSavingAllowed>
<EribFinesLoadingAutoretry>true</EribFinesLoadingAutoretry>
<EribStatePaymentShortCutsEnabled>true</EribStatePaymentShortCutsEnabled>
<EribAfterPayInfoEnabled>true</EribAfterPayInfoEnabled>
<EribServicesDeeplinkEnabled>true</EribServicesDeeplinkEnabled>
<EribPenaltyInPaymentProcessEnabled>true</EribPenaltyInPaymentProcessEnabled>
<EribPenaltyDocumentsMigration>true</EribPenaltyDocumentsMigration>
<overseasTransfer>true</overseasTransfer>
<importantInfoEnabled>false</importantInfoEnabled>
<historyRouterEnabled>true</historyRouterEnabled>
<SBTelecomSectionOnlyForClients>false</SBTelecomSectionOnlyForClients>
<webAnalyticsEnabled>true</webAnalyticsEnabled>
<newSectionInvestEnable>true</newSectionInvestEnable>
<newProductsVC>true</newProductsVC>
<newProductsVCv2>true</newProductsVCv2>
<hidingSectionEnabled>true</hidingSectionEnabled>
<orderingSectionEnabled>true</orderingSectionEnabled>
<hidingSectionTutorialEnabled>false</hidingSectionTutorialEnabled>
<arrestInfoService>true</arrestInfoService>
<FastLoginApp>false</FastLoginApp>
<PrintAutoSubscriptionCheck>true</PrintAutoSubscriptionCheck>
<productNavigationBarMod>3</productNavigationBarMod>
<IsFromAddrBook>true</IsFromAddrBook>
<InstantApp>true</InstantApp>
<InstantAppV2>true</InstantAppV2>
<mobilePOSEnabled>true</mobilePOSEnabled>
<earlyLoanRepayment>true</earlyLoanRepayment>
<newProductDetailsUIEnabled>true</newProductDetailsUIEnabled>
<newProductDetailsContentEnabled>true</newProductDetailsContentEnabled>
<PaymentTransactionsPopUpConfirmNumber>true</PaymentTransactionsPopUpConfirmNumber>
<soundsInAppEnabled>true</soundsInAppEnabled>
<googleMapsEnabled>false</googleMapsEnabled>
<messengerFirstLoginEnabled>false</messengerFirstLoginEnabled>
<authBlockingScreen>true</authBlockingScreen>
<PrintAutoSubscriptionTutorialCheck>true</PrintAutoSubscriptionTutorialCheck>
<balanceFromPush>true</balanceFromPush>
</node>
<node id="10.21.152.7">
<coreQR>true</coreQR>
<SBTelecom>true</SBTelecom>
<CreditRating>false</CreditRating>
<CreditRating_v2>false</CreditRating_v2>
<OKBRating>true</OKBRating>
<EnableBetaVersion>
<version>8.1.2</version>
<version>8.1.1</version>
</EnableBetaVersion>
<enableArrests>true</enableArrests>
<cardDelivery>true</cardDelivery>
<loanTable>true</loanTable>
<hideRegion>true</hideRegion>
<pciDss>true</pciDss>
<cashByCode>true</cashByCode>
<selfTransfer>true</selfTransfer>
<selfTransferP2P>true</selfTransferP2P>
<selfTransferStorno>true</selfTransferStorno>
<creditCardAutorepayment>true</creditCardAutorepayment>
<governmentServices>true</governmentServices>
<pensionTransfer>true</pensionTransfer>
<pensionCertificate>true</pensionCertificate>
<governmentServices_actual>true</governmentServices_actual>
<pensionTransfer_actual>true</pensionTransfer_actual>
<pensionCertificate_actual>true</pensionCertificate_actual>
<pensionRegistration>true</pensionRegistration>
<governmentAnimationSearching>true</governmentAnimationSearching>
<blockedCardsStatusWay4>true</blockedCardsStatusWay4>
<autoTransfer>true</autoTransfer>
<UFSHost>sbt-oafs-498.sigma.sbrf.ru:443</UFSHost>
<coreCreditCardInfo_v2>true</coreCreditCardInfo_v2>
<coreCreditCardInfo_v3>true</coreCreditCardInfo_v3>
<OmniChannelHistory>true</OmniChannelHistory>
<showUfsHistoryOperations>true</showUfsHistoryOperations>
<showSpasibo>true</showSpasibo>
<enableContactMangager>true</enableContactMangager>
<AuthCyrrilicKeypadEnabled>true</AuthCyrrilicKeypadEnabled>
<showCorporateCard>true</showCorporateCard>
<autoTouchID>true</autoTouchID>
<suggestionsEnabled>true</suggestionsEnabled>
<historyList_v2>true</historyList_v2>
<shimmersEnabled>true</shimmersEnabled>
<early2018EnterAnimation>true</early2018EnterAnimation>
<fastLoginOnMessengerPushEnabled>true</fastLoginOnMessengerPushEnabled>
<currenciesInOperationsVCEnabled>false</currenciesInOperationsVCEnabled>
<EribPenaltyDocumentsSavingAllowed>true</EribPenaltyDocumentsSavingAllowed>
<EribFinesLoadingAutoretry>true</EribFinesLoadingAutoretry>
<EribStatePaymentShortCutsEnabled>true</EribStatePaymentShortCutsEnabled>
<EribAfterPayInfoEnabled>true</EribAfterPayInfoEnabled>
<EribServicesDeeplinkEnabled>true</EribServicesDeeplinkEnabled>
<EribPenaltyInPaymentProcessEnabled>true</EribPenaltyInPaymentProcessEnabled>
<EribPenaltyDocumentsMigration>true</EribPenaltyDocumentsMigration>
<overseasTransfer>true</overseasTransfer>
<importantInfoEnabled>false</importantInfoEnabled>
<historyRouterEnabled>true</historyRouterEnabled>
<SBTelecomSectionOnlyForClients>false</SBTelecomSectionOnlyForClients>
<webAnalyticsEnabled>true</webAnalyticsEnabled>
<newSectionInvestEnable>true</newSectionInvestEnable>
<newProductsVC>true</newProductsVC>
<newProductsVCv2>true</newProductsVCv2>
<hidingSectionEnabled>true</hidingSectionEnabled>
<orderingSectionEnabled>true</orderingSectionEnabled>
<hidingSectionTutorialEnabled>false</hidingSectionTutorialEnabled>
<arrestInfoService>true</arrestInfoService>
<FastLoginApp>false</FastLoginApp>
<PrintAutoSubscriptionCheck>false</PrintAutoSubscriptionCheck>
<productNavigationBarMod>3</productNavigationBarMod>
<IsFromAddrBook>true</IsFromAddrBook>
<InstantApp>true</InstantApp>
<InstantAppV2>true</InstantAppV2>
<mobilePOSEnabled>true</mobilePOSEnabled>
<earlyLoanRepayment>true</earlyLoanRepayment>
<newProductDetailsUIEnabled>true</newProductDetailsUIEnabled>
<newProductDetailsContentEnabled>true</newProductDetailsContentEnabled>
<PaymentTransactionsPopUpConfirmNumber>true</PaymentTransactionsPopUpConfirmNumber>
<soundsInAppEnabled>true</soundsInAppEnabled>
<googleMapsEnabled>false</googleMapsEnabled>
<messengerFirstLoginEnabled>false</messengerFirstLoginEnabled>
<authBlockingScreen>true</authBlockingScreen>
<PrintAutoSubscriptionTutorialCheck>true</PrintAutoSubscriptionTutorialCheck>
<balanceFromPush>true</balanceFromPush>
</node>
<node id="ift-c-mp.testonline.sberbank.ru">
<coreQR>true</coreQR>
<SBTelecom>true</SBTelecom>
<CreditRating>false</CreditRating>
<CreditRating_v2>false</CreditRating_v2>
<OKBRating>true</OKBRating>
<EnableBetaVersion>
<version>8.1.2</version>
<version>8.1.1</version>
</EnableBetaVersion>
<enableArrests>true</enableArrests>
<cardDelivery>true</cardDelivery>
<loanTable>true</loanTable>
<hideRegion>true</hideRegion>
<pciDss>true</pciDss>
<cashByCode>true</cashByCode>
<selfTransfer>true</selfTransfer>
<selfTransferP2P>true</selfTransferP2P>
<selfTransferStorno>true</selfTransferStorno>
<creditCardAutorepayment>true</creditCardAutorepayment>
<governmentServices>true</governmentServices>
<pensionTransfer>true</pensionTransfer>
<pensionCertificate>true</pensionCertificate>
<governmentServices_actual>true</governmentServices_actual>
<pensionTransfer_actual>true</pensionTransfer_actual>
<pensionCertificate_actual>true</pensionCertificate_actual>
<pensionRegistration>true</pensionRegistration>
<governmentAnimationSearching>true</governmentAnimationSearching>
<blockedCardsStatusWay4>true</blockedCardsStatusWay4>
<autoTransfer>true</autoTransfer>
<UFSHost>ift.testefs.sberbank.ru:443</UFSHost>
<coreCreditCardInfo_v2>true</coreCreditCardInfo_v2>
<coreCreditCardInfo_v3>true</coreCreditCardInfo_v3>
<OmniChannelHistory>true</OmniChannelHistory>
<showUfsHistoryOperations>true</showUfsHistoryOperations>
<showSpasibo>true</showSpasibo>
<enableContactMangager>true</enableContactMangager>
<AuthCyrrilicKeypadEnabled>true</AuthCyrrilicKeypadEnabled>
<showCorporateCard>true</showCorporateCard>
<autoTouchID>true</autoTouchID>
<suggestionsEnabled>true</suggestionsEnabled>
<historyList_v2>true</historyList_v2>
<shimmersEnabled>true</shimmersEnabled>
<skeletonsEnabled>true</skeletonsEnabled>
<early2018EnterAnimation>true</early2018EnterAnimation>
<fastLoginOnMessengerPushEnabled>true</fastLoginOnMessengerPushEnabled>
<currenciesInOperationsVCEnabled>false</currenciesInOperationsVCEnabled>
<EribPenaltyDocumentsSavingAllowed>true</EribPenaltyDocumentsSavingAllowed>
<EribFinesLoadingAutoretry>true</EribFinesLoadingAutoretry>
<EribStatePaymentShortCutsEnabled>true</EribStatePaymentShortCutsEnabled>
<EribAfterPayInfoEnabled>true</EribAfterPayInfoEnabled>
<EribServicesDeeplinkEnabled>true</EribServicesDeeplinkEnabled>
<EribPenaltyInPaymentProcessEnabled>true</EribPenaltyInPaymentProcessEnabled>
<EribPenaltyDocumentsMigration>true</EribPenaltyDocumentsMigration>
<overseasTransfer>true</overseasTransfer>
<importantInfoEnabled>false</importantInfoEnabled>
<historyRouterEnabled>true</historyRouterEnabled>
<SBTelecomSectionOnlyForClients>false</SBTelecomSectionOnlyForClients>
<webAnalyticsEnabled>true</webAnalyticsEnabled>
<newSectionInvestEnable>true</newSectionInvestEnable>
<newProductsVC>true</newProductsVC>
<newProductsVCv2>true</newProductsVCv2>
<hidingSectionEnabled>true</hidingSectionEnabled>
<orderingSectionEnabled>true</orderingSectionEnabled>
<hidingSectionTutorialEnabled>false</hidingSectionTutorialEnabled>
<arrestInfoService>true</arrestInfoService>
<FastLoginApp>false</FastLoginApp>
<PrintAutoSubscriptionCheck>true</PrintAutoSubscriptionCheck>
<productNavigationBarMod>3</productNavigationBarMod>
<IsFromAddrBook>true</IsFromAddrBook>
<InstantApp>true</InstantApp>
<InstantAppV2>true</InstantAppV2>
<mobilePOSEnabled>true</mobilePOSEnabled>
<earlyLoanRepayment>true</earlyLoanRepayment>
<newProductDetailsUIEnabled>true</newProductDetailsUIEnabled>
<newProductDetailsContentEnabled>true</newProductDetailsContentEnabled>
<PaymentTransactionsPopUpConfirmNumber>true</PaymentTransactionsPopUpConfirmNumber>
<soundsInAppEnabled>true</soundsInAppEnabled>
<googleMapsEnabled>false</googleMapsEnabled>
<messengerFirstLoginEnabled>false</messengerFirstLoginEnabled>
<authBlockingScreen>true</authBlockingScreen>
<PrintAutoSubscriptionTutorialCheck>true</PrintAutoSubscriptionTutorialCheck>
<balanceFromPush>true</balanceFromPush>
</node>
</nodes>
</param>
<param name="NominalAccounts" description="Право работать с номинальными счетами">
<type>setting</type>
<enabled>true</enabled>
</param>
<param name="arrestInfoService" description="">
<type>setting</type>
<enabled>true</enabled>
<bankruptUrl>
https://www.sberbank.ru/ru/person/help-center/bankrupt
</bankruptUrl>
<arrestInfoUrl>https://www.sberbank.ru/ru/person/seizure</arrestInfoUrl>
<phoneFSSP>8 800 250-39-32</phoneFSSP>
<workingHoursFSSP>по будням 9:00 — 18:00 (МСК)</workingHoursFSSP>
</param>
<param name="ufsOperationDetailHistoryAlert" description="">
<type>strings</type>
<strings>
<string localeId="ru">
Вы не можете просмотреть данную операцию через мобильное приложение. Для просмотра воспользуйтесь Web версией Сбербанк Онлайн.
</string>
</strings>
</param>
<param name="integrationPlatform" description="">
<type>list</type>
<nodes>
<node id="greenfield2.online.sberbank.ru">
<startSessionUFS7>true</startSessionUFS7>
</node>
<node id="mobile.sberbank.ru">
<startSessionUFS7>true</startSessionUFS7>
</node>
<node id="ift-node0-mp.testonline.sberbank.ru">
<serviceSessionForUFS6AndUFS7>false</serviceSessionForUFS6AndUFS7>
<startSessionUFS7>true</startSessionUFS7>
</node>
<node id="ift-node1-mp.testonline.sberbank.ru">
<serviceSessionForUFS6AndUFS7>false</serviceSessionForUFS6AndUFS7>
<startSessionUFS7>false</startSessionUFS7>
<pathUFS7>/sm-uko/v2/session/create</pathUFS7>
<pathUFS6>/client-session/ufsapi/sbol/v1/session/create</pathUFS6>
<pathUFS>/client-session/ufsapi/sbol/v1/session/create</pathUFS>
</node>
<node id="ift-node2-mp.testonline.sberbank.ru">
<serviceSessionForUFS6AndUFS7>false</serviceSessionForUFS6AndUFS7>
<startSessionUFS7>true</startSessionUFS7>
</node>
<node id="ift-node5-mp.testonline.sberbank.ru">
<serviceSessionForUFS6AndUFS7>false</serviceSessionForUFS6AndUFS7>
<startSessionUFS7>true</startSessionUFS7>
<pathUFSToMigrate>/sm-uko/v2/session/create</pathUFSToMigrate>
</node>
</nodes>
</param>
<param name="extendedPermission" description="">
<type>list</type>
<nodes>
<node id="ift-node1-mp.testonline.sberbank.ru">
<extendedPermissionEnabled>true</extendedPermissionEnabled>
<disabledPermissions>false</disabledPermissions>
</node>
<node id="ift-node2-mp.testonline.sberbank.ru">
<extendedPermissionEnabled>true</extendedPermissionEnabled>
<disabledPermissions>false</disabledPermissions>
</node>
<node id="mobile.sberbank.ru">
<extendedPermissionEnabled>true</extendedPermissionEnabled>
<disabledPermissions>false</disabledPermissions>
</node>
<node id="10.21.152.7">
<extendedPermissionEnabled>true</extendedPermissionEnabled>
<disabledPermissions>false</disabledPermissions>
</node>
<node id="greenfield1.online.sberbank.ru">
<extendedPermissionEnabled>true</extendedPermissionEnabled>
<disabledPermissions>false</disabledPermissions>
</node>
<node id="greenfield2.online.sberbank.ru">
<extendedPermissionEnabled>true</extendedPermissionEnabled>
<disabledPermissions>false</disabledPermissions>
</node>
<node id="node0.online.sberbank.ru">
<extendedPermissionEnabled>true</extendedPermissionEnabled>
<disabledPermissions>false</disabledPermissions>
</node>
<node id="node1.online.sberbank.ru">
<extendedPermissionEnabled>true</extendedPermissionEnabled>
<disabledPermissions>false</disabledPermissions>
</node>
<node id="node2.online.sberbank.ru">
<extendedPermissionEnabled>true</extendedPermissionEnabled>
<disabledPermissions>false</disabledPermissions>
</node>
<node id="node3.online.sberbank.ru">
<extendedPermissionEnabled>true</extendedPermissionEnabled>
<disabledPermissions>false</disabledPermissions>
</node>
<node id="node4.online.sberbank.ru">
<extendedPermissionEnabled>true</extendedPermissionEnabled>
<disabledPermissions>false</disabledPermissions>
</node>
</nodes>
</param>
<param name="SelfRegistrationCSAmApi" description="Включение mAPI на этапе саморегистрации в мобильном приложении">
<type>setting</type>
<enabled>true</enabled>
</param>
<param name="aim_withDeposit" description="Открытие цели с выбором типа вклада">
<type>setting</type>
<enabled>true</enabled>
</param>
<param description="" name="pushErib">
<type>setting</type>
<enabled>true</enabled>
</param>
<param name="EasyLogin" description="Включение новых правил создания логина">
<type>setting</type>
<enabled>true</enabled>
</param>
<param name="visa_tokenization_new" description="">
<type>setting</type>
<enabled>false</enabled>
</param>
<param name="invoicing_8.0" description="Инвойсинг">
<type>service</type>
<enabled>true</enabled>
</param>
<param name="non_accept_8.0" description="Безакцептное списание">
<type>service</type>
<enabled>true</enabled>
<value>2000</value>
</param>
<param name="SpecialTutorialUID" description="Туториалы из списка 'специальные' и должны показываться при каждой регистрации">
<tutorials>
<tutorial UID="TutorialIncognitoKey"/>
<tutorial UID="TutorialAnalyticsAgreement"/>
<tutorial UID="TutorialStatementsKey"/>
</tutorials>
</param>
<param name="AllowedTutorialUID" description="Туториалы разрешенные к показу">
<tutorials>
<tutorial UID="TutorialIncognitoKey"/>
<tutorial UID="TutorialAnalyticsAgreement"/>
<tutorial UID="TGPTutorialDataSource"/>
<tutorial UID="TutorialStatementsKey"/>
<tutorial UID="TransactionPushTutorialKey"/>
<tutorial UID="TutorialApplePayKey"/>
<tutorial UID="TutorialVOTChatKey"/>
<tutorial UID="CALCarLoanTutorialIdentifier"/>
<tutorial UID="TutorialCCPKey"/>
<tutorial UID="TutorialPriorityCardKey"/>
</tutorials>
</param>
<param name="iOSAppDesing" description="Парамтеры iOS App Design">
<registrationLicenceLink>
http://www.sberbank.ru/common/img/uploaded/files/pdf/policy.pdf
</registrationLicenceLink>
<p2pMaxLimit>1000000</p2pMaxLimit>
<specialP2PMaxLimit>5000000</specialP2PMaxLimit>
<accountNumber>true</accountNumber>
<registrationPrimaryFlowByCardNumber>true</registrationPrimaryFlowByCardNumber>
<regNotSberbankCardError>true</regNotSberbankCardError>
<abTests>true</abTests>
<autofillEnabled>true</autofillEnabled>
<siriShortcutsEnabled>true</siriShortcutsEnabled>
<combinedRegistration>true</combinedRegistration>
<newFocusStyle>true</newFocusStyle>
<newTextsForRegistrationEnabled>true</newTextsForRegistrationEnabled>
<requestAnalyticsEnabled>true</requestAnalyticsEnabled>
<depositPromoBanner>
<enabled>true</enabled>
<closeButtonEnabled>true</closeButtonEnabled>
<version>1</version>
<title>Открыть вклад</title>
<description>На выгодных условиях</description>
<backgroundColor>0xF1F3FC</backgroundColor>
</depositPromoBanner>
</param>
<param name="geoservice" description="Настройка URL гео-сервисов для блоков">
<type>list</type>
<nodes>
<node id="node0.online.sberbank.ru">
<host>https://geo1.online.sberbank.ru/</host>
<yandexMapExperiment>false</yandexMapExperiment>
</node>
<node id="node2.online.sberbank.ru">
<host>https://geo1.online.sberbank.ru/</host>
<yandexMapExperiment>false</yandexMapExperiment>
</node>
<node id="node3.online.sberbank.ru">
<host>https://geo1.online.sberbank.ru/</host>
<yandexMapExperiment>false</yandexMapExperiment>
</node>
<node id="node4.online.sberbank.ru">
<host>https://geo1.online.sberbank.ru/</host>
<yandexMapExperiment>false</yandexMapExperiment>
</node>
<node id="greenfield1.online.sberbank.ru">
<yandexMapExperiment>true</yandexMapExperiment>
</node>
<node id="greenfield2.online.sberbank.ru">
<yandexMapExperiment>true</yandexMapExperiment>
</node>
<node id="mobile.sberbank.ru" description="Стенд ПСИ">
<host>https://push-t.sberbank.ru:1112/</host>
<yandexMapExperiment>true</yandexMapExperiment>
</node>
<node id="ift-node1-mp.testonline.sberbank.ru" description="Стенд ИФТ блок 1 (мобильный)">
<host>https://push-t.sberbank.ru:1112/</host>
<yandexMapExperiment>true</yandexMapExperiment>
</node>
<node id="ift-node2-mp.testonline.sberbank.ru" description="Стенд ИФТ блок 2 (мобильный)">
<host>https://push-t.sberbank.ru:1112/</host>
<yandexMapExperiment>true</yandexMapExperiment>
</node>
</nodes>
</param>
<param name="disabledFrameworks" description="Функционал отключения зависимостей">
<enabled>true</enabled>
<remoteToggleEnabled>true</remoteToggleEnabled>
<disabledAnalytics>
<analytics>Tune</analytics>
</disabledAnalytics>
</param>
<param name="lastToggleV2" description="Уведомление о принудительном обновлении в МП">
<enabled>true</enabled>
<lastToggleVerstion>9.5</lastToggleVerstion>
<lastToggleDate>1639129600</lastToggleDate>
<appStoreLink>
https%3A%2F%2Fitunes.apple.com%2Fru%2Fapp%2F%25D1%2581%25D0%25B1%25D0%25B5%25D1%2580%25D0%25B1%25D0%25B0%25D0%25BD%25D0%25BA-%25D0%25BE%25D0%25BD%25D0%25BB%25D0%25B0%25D0%25B9%25D0%25BD%2Fid492224193%3Fmt%3D8
</appStoreLink>
<appWebLink>
https%3A%2F%2Fonline.sberbank.ru%2FCSAFront%2Findex.do
</appWebLink>
<lastToggleSDK>9.0</lastToggleSDK>
<lastTogglePeriod>0</lastTogglePeriod>
<lastToggleDevice>
<device>iPhone</device>
<device>iPhone 3G</device>
<device>iPhone 3GS</device>
<device>iPhone 4</device>
</lastToggleDevice>
<messageText>
Вышла новая версия приложения. Чтобы вам было доступно еще больше услуг, обновите приложение через AppStore.
</messageText>
<upMessageText>
Версия приложения устарела и больше не работает. Чтобы воспользоваться приложением: 1. Обновите операционную систему: зайдите в Настройки – Основные – Обновление ПО – Установить. 2. После этого обновите приложение до рабочей версии.
</upMessageText>
<errorText>
Версия приложения устарела и больше не работает. Чтобы воспользоваться приложением, его нужно обновить через AppStore.
</errorText>
<fatalErrorText>
Версия приложения устарела и больше не поддерживается на вашем телефоне. Вы можете использовать сайт Сбербанк Онлайн.
</fatalErrorText>
</param>
<param name="signOnParams" description="Парамтеры стрима SignOn">
<type>list</type>
<offerNonAccept>
http://www.sberbank.ru/common/img/uploaded/files/pdf/usloviya_perevoda.pdf
</offerNonAccept>
<merchantDataManagementServiceName>Управление Сбербанк ID</merchantDataManagementServiceName>
<nodes>
<node id="node0.online.sberbank.ru">
<qrPayments>true</qrPayments>
<qrP2P>true</qrP2P>
<qrMerchantBinding>true</qrMerchantBinding>
<universalLinks>true</universalLinks>
<invoicing>true</invoicing>
<nonAccept>
<enabled>false</enabled>
<value>2000</value>
</nonAccept>
<merchantDataManagement>true</merchantDataManagement>
</node>
<node id="node1.online.sberbank.ru">
<qrPayments>true</qrPayments>
<qrP2P>true</qrP2P>
<qrMerchantBinding>true</qrMerchantBinding>
<universalLinks>true</universalLinks>
<invoicing>true</invoicing>
<nonAccept>
<enabled>false</enabled>
<value>2000</value>
</nonAccept>
<merchantDataManagement>true</merchantDataManagement>
</node>
<node id="node2.online.sberbank.ru">
<qrPayments>true</qrPayments>
<qrP2P>true</qrP2P>
<qrMerchantBinding>true</qrMerchantBinding>
<universalLinks>true</universalLinks>
<invoicing>true</invoicing>
<nonAccept>
<enabled>false</enabled>
<value>2000</value>
</nonAccept>
<merchantDataManagement>true</merchantDataManagement>
</node>
<node id="node3.online.sberbank.ru">
<qrPayments>true</qrPayments>
<qrP2P>true</qrP2P>
<qrMerchantBinding>true</qrMerchantBinding>
<universalLinks>true</universalLinks>
<invoicing>true</invoicing>
<nonAccept>
<enabled>false</enabled>
<value>2000</value>
</nonAccept>
<merchantDataManagement>true</merchantDataManagement>
</node>
<node id="greenfield1.online.sberbank.ru">
<qrPayments>true</qrPayments>
<qrP2P>true</qrP2P>
<qrMerchantBinding>true</qrMerchantBinding>
<universalLinks>true</universalLinks>
<invoicing>true</invoicing>
<nonAccept>
<enabled>true</enabled>
<value>2000</value>
</nonAccept>
<merchantDataManagement>true</merchantDataManagement>
</node>
<node id="greenfield2.online.sberbank.ru">
<qrPayments>true</qrPayments>
<qrP2P>true</qrP2P>
<qrMerchantBinding>true</qrMerchantBinding>
<universalLinks>true</universalLinks>
<invoicing>true</invoicing>
<nonAccept>
<enabled>true</enabled>
<value>2000</value>
</nonAccept>
<merchantDataManagement>true</merchantDataManagement>
</node>
<node id="194.186.207.23">
<qrPayments>true</qrPayments>
<qrP2P>true</qrP2P>
<qrMerchantBinding>true</qrMerchantBinding>
<universalLinks>true</universalLinks>
<invoicing>true</invoicing>
<nonAccept>
<enabled>true</enabled>
<value>2000</value>
</nonAccept>
<merchantDataManagement>true</merchantDataManagement>
</node>
<node id="ift-node1.testonline.sberbank.ru">
<qrPayments>true</qrPayments>
<qrP2P>true</qrP2P>
<qrMerchantBinding>true</qrMerchantBinding>
<universalLinks>true</universalLinks>
<invoicing>true</invoicing>
<nonAccept>
<enabled>true</enabled>
<value>2000</value>
</nonAccept>
<merchantDataManagement>true</merchantDataManagement>
</node>
<node id="ift-node2.testonline.sberbank.ru">
<qrPayments>true</qrPayments>
<qrP2P>true</qrP2P>
<qrMerchantBinding>true</qrMerchantBinding>
<universalLinks>true</universalLinks>
<invoicing>true</invoicing>
<nonAccept>
<enabled>true</enabled>
<value>2000</value>
</nonAccept>
<merchantDataManagement>true</merchantDataManagement>
</node>
<node id="ift-node1-mp.testonline.sberbank.ru">
<qrPayments>true</qrPayments>
<qrP2P>true</qrP2P>
<qrMerchantBinding>true</qrMerchantBinding>
<universalLinks>true</universalLinks>
<invoicing>true</invoicing>
<nonAccept>
<enabled>true</enabled>
<value>2000</value>
</nonAccept>
<merchantDataManagement>true</merchantDataManagement>
</node>
<node id="ift-node2-mp.testonline.sberbank.ru">
<qrPayments>true</qrPayments>
<qrP2P>true</qrP2P>
<qrMerchantBinding>true</qrMerchantBinding>
<universalLinks>true</universalLinks>
<invoicing>true</invoicing>
<nonAccept>
<enabled>true</enabled>
<value>2000</value>
</nonAccept>
<merchantDataManagement>true</merchantDataManagement>
</node>
<node id="mobile.sberbank.ru">
<qrPayments>true</qrPayments>
<qrP2P>true</qrP2P>
<qrMerchantBinding>true</qrMerchantBinding>
<universalLinks>true</universalLinks>
<invoicing>true</invoicing>
<nonAccept>
<enabled>true</enabled>
<value>2000</value>
</nonAccept>
<merchantDataManagement>true</merchantDataManagement>
</node>
</nodes>
</param>
<param name="aim_withCurrency" description="Открытие валютных целей">
<type>setting</type>
<enabled>true</enabled>
</param>
<param name="offers" description="Предложения продуктов на витринах продаж">
<type>list</type>
<enabled>true</enabled>
<mainScreen>
<enabled>true</enabled>
<limit>2147483647</limit>
<expandedOffers>true</expandedOffers>
<electionsOffers>false</electionsOffers>
</mainScreen>
<successScreen>
<enabled>true</enabled>
<limit>2147483647</limit>
</successScreen>
<mainScreenStories>
<enabled>true</enabled>
<limit>2147483647</limit>
<closed>true</closed>
<opened>false</opened>
</mainScreenStories>
<products>
<product name="Universal">
<url>
http://lightapp.ru/config/salestools/unknown/index.html
</url>
<actionTitle>Далее</actionTitle>
</product>
<product name="MobilePhoneAutopayment">
<url>
http://lightapp.ru/config/salestools/mobile_phone_autopayment/index.html
</url>
<actionTitle>Далее</actionTitle>
</product>
<product name="AutopaymentSetting">
<url>
http://lightapp.ru/config/salestools/autopayment_setting/index.html
</url>
<actionTitle>Далее</actionTitle>
</product>
<product name="Deposit">
<url>
http://lightapp.ru/config/salestools/deposit/index.html
</url>
<actionTitle>Далее</actionTitle>
</product>
<product name="FamilyHead">
<url>
http://lightapp.ru/config/salestools/family_head/index.html
</url>
<actionTitle>Далее</actionTitle>
</product>
<product name="PensionTransfer">
<url>
http://lightapp.ru/config/salestools/pension_transfer/index.html
</url>
<actionTitle>Далее</actionTitle>
</product>
<product name="RelativesProtection">
<url>
http://lightapp.ru/config/salestools/relativesprotection/index.html
</url>
<actionTitle>Далее</actionTitle>
</product>
<product name="CreateMoneybox">
<url>
http://lightapp.ru/config/salestools/create_moneybox/index.html
</url>
<actionTitle>Далее</actionTitle>
</product>
<product name="CreditCard">
<url>
http://lightapp.ru/config/salestools/credit_card/index.html
</url>
<actionTitle>Далее</actionTitle>
</product>
<product name="TransferBetweenMyAccounts">
<url>
http://lightapp.ru/config/salestools/transfer_between_my_accounts/index.html
</url>
<actionTitle>Далее</actionTitle>
</product>
<product name="TransferByCardNumber">
<url>
http://lightapp.ru/config/salestools/transfer_by_card_number/index.html
</url>
<actionTitle>Далее</actionTitle>
</product>
<product name="TransferByPhoneNumber">
<url>
http://lightapp.ru/config/salestools/transfer_by_phone_number/index.html
</url>
<actionTitle>Далее</actionTitle>
</product>
<product name="MortgageInsurance">
<url>
http://lightapp.ru/config/salestools/mortgage_insurance/index.html
</url>
<actionTitle>Далее</actionTitle>
</product>
<product name="TravelInsurance">
<url>
http://lightapp.ru/config/salestools/travel_insurance/index.html
</url>
<actionTitle>Далее</actionTitle>
</product>
<product name="CreateTarget">
<url>
http://lightapp.ru/config/salestools/create_target/index.html
</url>
<actionTitle>Далее</actionTitle>
</product>
</products>
</param>
<param name="offersAndStories" description="Предложения продуктов и истории на витринах продаж">
<type>list</type>
<enabled>true</enabled>
<nodes>
<node id="ift-node1.testonline.sberbank.ru">
<enabled>true</enabled>
<settings>
<cache>
<lifetimeOfIcons>129600</lifetimeOfIcons>
<lifetimeOfImages>20160</lifetimeOfImages>
</cache>
</settings>
<mainScreen>
<enabled>true</enabled>
<limit>2147483647</limit>
<closed>true</closed>
<opened>false</opened>
<backendTipsBroker>false</backendTipsBroker>
</mainScreen>
<mainScreenDeposits>
<enabled>true</enabled>
<limit>5</limit>
</mainScreenDeposits>
<mainScreenLoans>
<enabled>true</enabled>
<limit>5</limit>
</mainScreenLoans>
<mainScreenCards>
<enabled>true</enabled>
<limit>5</limit>
</mainScreenCards>
<successScreen>
<enabled>true</enabled>
<limit>2147483647</limit>
<backendTipsBroker>false</backendTipsBroker>
</successScreen>
<mainScreenStories>
<enabled>true</enabled>
<limit>2147483647</limit>
<closed>false</closed>
<opened>false</opened>
<backendTipsBroker>false</backendTipsBroker>
<title>Рекомендуем</title>
<no_offers_text>
Для вас пока нет рекомендаций, но они скоро появятся
</no_offers_text>
<preloadCount>1</preloadCount>
<lifetimeOfCache>5</lifetimeOfCache>
<cache>true</cache>
<lifetimeOfCachePermissions>2</lifetimeOfCachePermissions>
<cachePermissions>true</cachePermissions>
<reloadSection>true</reloadSection>
</mainScreenStories>
<mainScreenTutorial>
<enabled>false</enabled>
<limit>10</limit>
<backendTipsBroker>false</backendTipsBroker>
</mainScreenTutorial>
<marketplaceStories>
<enabled>true</enabled>
<limit>214748364</limit>
<closed>false</closed>
<opened>false</opened>
<title>Рекомендуем</title>
<no_offers_text>
Для вас пока нет рекомендаций, но они скоро появятся
</no_offers_text>
<preloadCount>1</preloadCount>
<lifetimeOfCache>5</lifetimeOfCache>
<cache>true</cache>
<lifetimeOfCachePermissions>7</lifetimeOfCachePermissions>
<cachePermissions>true</cachePermissions>
</marketplaceStories>
<paymentsHistoryScreen>
<enabled>true</enabled>
<limit>1</limit>
<formNames>
<formName>ExtCardTransferIn</formName>
<formName>ExtCardOtherIn</formName>
<formName>ExtCardCashIn</formName>
</formNames>
<minSumRUB>500</minSumRUB>
<maxSumRUB>100000000</maxSumRUB>
<termDays>365</termDays>
<backendTipsBroker>false</backendTipsBroker>
</paymentsHistoryScreen>
</node>
<node id="ift-node2.testonline.sberbank.ru">
<enabled>true</enabled>
<settings>
<cache>
<lifetimeOfIcons>129600</lifetimeOfIcons>
<lifetimeOfImages>20160</lifetimeOfImages>
</cache>
</settings>
<mainScreen>
<enabled>true</enabled>
<limit>2147483647</limit>
<closed>true</closed>
<opened>false</opened>
<mvpEnabled>true</mvpEnabled>
<backendTipsBroker>false</backendTipsBroker>
</mainScreen>
<mainScreenDeposits>
<enabled>true</enabled>
<limit>1</limit>
</mainScreenDeposits>
<mainScreenLoans>
<enabled>true</enabled>
<limit>1</limit>
</mainScreenLoans>
<mainScreenCards>
<enabled>true</enabled>
<limit>1</limit>
</mainScreenCards>
<successScreen>
<enabled>true</enabled>
<limit>2147483647</limit>
<backendTipsBroker>false</backendTipsBroker>
</successScreen>
<mainScreenStories>
<enabled>true</enabled>
<limit>2147483647</limit>
<closed>false</closed>
<opened>false</opened>
<backendTipsBroker>true</backendTipsBroker>
<title>Рекомендуем</title>
<no_offers_text>
Для вас пока нет рекомендаций, но они скоро появятся
</no_offers_text>
<preloadCount>1</preloadCount>
<lifetimeOfCache>5</lifetimeOfCache>
<cache>true</cache>
<lifetimeOfCachePermissions>2</lifetimeOfCachePermissions>
<cachePermissions>true</cachePermissions>
<reloadSection>true</reloadSection>
</mainScreenStories>
<mainScreenTutorial>
<enabled>true</enabled>
<limit>10</limit>
<backendTipsBroker>false</backendTipsBroker>
</mainScreenTutorial>
<marketplaceStories>
<enabled>true</enabled>
<limit>2147483647</limit>
<closed>false</closed>
<opened>false</opened>
<title>Рекомендуем</title>
<no_offers_text>
Для вас пока нет рекомендаций, но они скоро появятся
</no_offers_text>
<preloadCount>1</preloadCount>
<lifetimeOfCache>5</lifetimeOfCache>
<cache>true</cache>
<lifetimeOfCachePermissions>7</lifetimeOfCachePermissions>
<cachePermissions>true</cachePermissions>
</marketplaceStories>
<paymentsHistoryScreen>
<enabled>true</enabled>
<limit>1</limit>
<formNames>
<formName>ExtCardTransferIn</formName>
<formName>ExtCardOtherIn</formName>
<formName>ExtCardCashIn</formName>
</formNames>
<minSumRUB>500</minSumRUB>
<maxSumRUB>100000000</maxSumRUB>
<termDays>365</termDays>
<backendTipsBroker>true</backendTipsBroker>
</paymentsHistoryScreen>
</node>
<node id="ift-node1-mp.testonline.sberbank.ru">
<enabled>true</enabled>
<settings>
<cache>
<lifetimeOfIcons>129600</lifetimeOfIcons>
<lifetimeOfImages>20160</lifetimeOfImages>
</cache>
</settings>
<mainScreen>
<enabled>true</enabled>
<limit>2147483647</limit>
<closed>true</closed>
<opened>false</opened>
<backendTipsBroker>false</backendTipsBroker>
</mainScreen>
<mainScreenDeposits>
<enabled>true</enabled>
<limit>5</limit>
</mainScreenDeposits>
<mainScreenLoans>
<enabled>true</enabled>
<limit>5</limit>
</mainScreenLoans>
<mainScreenCards>
<enabled>true</enabled>
<limit>5</limit>
</mainScreenCards>
<successScreen>
<enabled>true</enabled>
<limit>2147483647</limit>
<backendTipsBroker>false</backendTipsBroker>
</successScreen>
<mainScreenStories>
<enabled>true</enabled>
<limit>2147483647</limit>
<closed>false</closed>
<opened>false</opened>
<backendTipsBroker>false</backendTipsBroker>
<title>Рекомендуем</title>
<no_offers_text>
Для вас пока нет рекомендаций, но они скоро появятся
</no_offers_text>
<preloadCount>1</preloadCount>
<lifetimeOfCache>5</lifetimeOfCache>
<cache>true</cache>
<lifetimeOfCachePermissions>2</lifetimeOfCachePermissions>
<cachePermissions>true</cachePermissions>
<reloadSection>true</reloadSection>
</mainScreenStories>
<mainScreenTutorial>
<enabled>false</enabled>
<limit>10</limit>
<backendTipsBroker>false</backendTipsBroker>
</mainScreenTutorial>
<marketplaceStories>
<enabled>true</enabled>
<limit>2147483647</limit>
<closed>false</closed>
<opened>false</opened>
<title>Рекомендуем</title>
<no_offers_text>
Для вас пока нет рекомендаций, но они скоро появятся
</no_offers_text>
<preloadCount>1</preloadCount>
<lifetimeOfCache>5</lifetimeOfCache>
<cache>true</cache>
<lifetimeOfCachePermissions>7</lifetimeOfCachePermissions>
<cachePermissions>true</cachePermissions>
</marketplaceStories>
<paymentsHistoryScreen>
<enabled>true</enabled>
<limit>1</limit>
<formNames>
<formName>ExtCardTransferIn</formName>
<formName>ExtCardOtherIn</formName>
<formName>ExtCardCashIn</formName>
</formNames>
<minSumRUB>500</minSumRUB>
<maxSumRUB>100000000</maxSumRUB>
<termDays>365</termDays>
<backendTipsBroker>false</backendTipsBroker>
</paymentsHistoryScreen>
</node>
<node id="ift-node2-mp.testonline.sberbank.ru">
<enabled>true</enabled>
<settings>
<cache>
<lifetimeOfIcons>129600</lifetimeOfIcons>
<lifetimeOfImages>20160</lifetimeOfImages>
</cache>
</settings>
<mainScreen>
<enabled>true</enabled>
<limit>2147483647</limit>
<closed>true</closed>
<opened>false</opened>
<backendTipsBroker>false</backendTipsBroker>
</mainScreen>
<mainScreenDeposits>
<enabled>true</enabled>
<limit>1</limit>
</mainScreenDeposits>
<mainScreenLoans>
<enabled>true</enabled>
<limit>1</limit>
</mainScreenLoans>
<mainScreenCards>
<enabled>true</enabled>
<limit>1</limit>
</mainScreenCards>
<successScreen>
<enabled>true</enabled>
<limit>2147483647</limit>
<backendTipsBroker>false</backendTipsBroker>
</successScreen>
<mainScreenStories>
<enabled>true</enabled>
<limit>2147483647</limit>
<closed>false</closed>
<opened>false</opened>
<backendTipsBroker>false</backendTipsBroker>
<title>Рекомендуем</title>
<no_offers_text>
Для вас пока нет рекомендаций, но они скоро появятся
</no_offers_text>
<preloadCount>1</preloadCount>
<lifetimeOfCache>5</lifetimeOfCache>
<cache>true</cache>
<lifetimeOfCachePermissions>2</lifetimeOfCachePermissions>
<cachePermissions>true</cachePermissions>
<reloadSection>true</reloadSection>
</mainScreenStories>
<mainScreenTutorial>
<enabled>true</enabled>
<limit>10</limit>
<backendTipsBroker>false</backendTipsBroker>
</mainScreenTutorial>
<marketplaceStories>
<enabled>true</enabled>
<limit>2147483647</limit>
<closed>false</closed>
<opened>false</opened>
<title>Рекомендуем</title>
<no_offers_text>
Для вас пока нет рекомендаций, но они скоро появятся
</no_offers_text>
<preloadCount>1</preloadCount>
<lifetimeOfCache>5</lifetimeOfCache>
<cache>true</cache>
<lifetimeOfCachePermissions>7</lifetimeOfCachePermissions>
<cachePermissions>true</cachePermissions>
</marketplaceStories>
<paymentsHistoryScreen>
<enabled>true</enabled>
<limit>1</limit>
<formNames>
<formName>ExtCardTransferIn</formName>
<formName>ExtCardOtherIn</formName>
<formName>ExtCardCashIn</formName>
</formNames>
<minSumRUB>500</minSumRUB>
<maxSumRUB>100000000</maxSumRUB>
<termDays>365</termDays>
<backendTipsBroker>true</backendTipsBroker>
</paymentsHistoryScreen>
</node>
<node id="mobile.sberbank.ru">
<enabled>true</enabled>
<settings>
<cache>
<lifetimeOfIcons>129600</lifetimeOfIcons>
<lifetimeOfImages>20160</lifetimeOfImages>
</cache>
</settings>
<mainScreen>
<enabled>true</enabled>
<limit>214748364</limit>
<closed>false</closed>
<opened>false</opened>
<backendTipsBroker>false</backendTipsBroker>
</mainScreen>
<mainScreenDeposits>
<enabled>true</enabled>
<limit>1</limit>
</mainScreenDeposits>
<mainScreenLoans>
<enabled>true</enabled>
<limit>1</limit>
</mainScreenLoans>
<mainScreenCards>
<enabled>true</enabled>
<limit>1</limit>
</mainScreenCards>
<successScreen>
<enabled>true</enabled>
<limit>2147483647</limit>
<backendTipsBroker>false</backendTipsBroker>
</successScreen>
<mainScreenStories>
<enabled>true</enabled>
<limit>2147483647</limit>
<closed>false</closed>
<opened>false</opened>
<title>Рекомендуем</title>
<no_offers_text>
Для вас пока нет рекомендаций, но они скоро появятся
</no_offers_text>
<preloadCount>3</preloadCount>
<backendTipsBroker>false</backendTipsBroker>
<lifetimeOfCache>3</lifetimeOfCache>
<cache>true</cache>
<lifetimeOfCachePermissions>3</lifetimeOfCachePermissions>
<cachePermissions>true</cachePermissions>
<likeButtonIsDisabled>false</likeButtonIsDisabled>
</mainScreenStories>
<mainScreenTutorial>
<enabled>true</enabled>
<limit>10</limit>
<backendTipsBroker>false</backendTipsBroker>
</mainScreenTutorial>
<paymentsHistoryScreen>
<enabled>true</enabled>
<limit>1</limit>
<formNames>
<formName>ExtCardTransferIn</formName>
<formName>ExtCardOtherIn</formName>
<formName>ExtCardCashIn</formName>
</formNames>
<minSumRUB>500</minSumRUB>
<maxSumRUB>100000000</maxSumRUB>
<termDays>365</termDays>
<backendTipsBroker>false</backendTipsBroker>
</paymentsHistoryScreen>
</node>
<node id="greenfield1.online.sberbank.ru">
<enabled>true</enabled>
<settings>
<cache>
<lifetimeOfIcons>129600</lifetimeOfIcons>
<lifetimeOfImages>20160</lifetimeOfImages>
</cache>
</settings>
<mainScreen>
<enabled>false</enabled>
<limit>2147483647</limit>
<closed>true</closed>
<opened>false</opened>
<backendTipsBroker>true</backendTipsBroker>
</mainScreen>
<mainScreenDeposits>
<enabled>true</enabled>
<limit>1</limit>
</mainScreenDeposits>
<mainScreenLoans>
<enabled>true</enabled>
<limit>1</limit>
</mainScreenLoans>
<mainScreenCards>
<enabled>true</enabled>
<limit>1</limit>
</mainScreenCards>
<successScreen>
<enabled>true</enabled>
<limit>2147483647</limit>
<backendTipsBroker>false</backendTipsBroker>
</successScreen>
<mainScreenStories>
<enabled>true</enabled>
<limit>2147483647</limit>
<closed>false</closed>
<opened>false</opened>
<backendTipsBroker>false</backendTipsBroker>
<title>Рекомендуем</title>
<no_offers_text>
Для вас пока нет рекомендаций, но они скоро появятся
</no_offers_text>
<preloadCount>1</preloadCount>
<lifetimeOfCache>10080</lifetimeOfCache>
<cache>true</cache>
<lifetimeOfCachePermissions>10080</lifetimeOfCachePermissions>
<cachePermissions>false</cachePermissions>
</mainScreenStories>
<mainScreenTutorial>
<enabled>true</enabled>
<limit>10</limit>
<backendTipsBroker>false</backendTipsBroker>
</mainScreenTutorial>
<paymentsHistoryScreen>
<enabled>true</enabled>
<limit>1</limit>
<formNames>
<formName>ExtCardTransferIn</formName>
<formName>ExtCardOtherIn</formName>
<formName>ExtCardCashIn</formName>
</formNames>
<minSumRUB>500</minSumRUB>
<maxSumRUB>100000000</maxSumRUB>
<termDays>365</termDays>
<backendTipsBroker>false</backendTipsBroker>
</paymentsHistoryScreen>
</node>
<node id="node0.online.sberbank.ru">
<enabled>true</enabled>
<settings>
<cache>
<lifetimeOfIcons>129600</lifetimeOfIcons>
<lifetimeOfImages>20160</lifetimeOfImages>
</cache>
</settings>
<mainScreen>
<enabled>true</enabled>
<limit>2147483647</limit>
<closed>true</closed>
<opened>false</opened>
<backendTipsBroker>true</backendTipsBroker>
</mainScreen>
<mainScreenDeposits>
<enabled>true</enabled>
<limit>1</limit>
</mainScreenDeposits>
<mainScreenLoans>
<enabled>true</enabled>
<limit>1</limit>
</mainScreenLoans>
<mainScreenCards>
<enabled>true</enabled>
<limit>1</limit>
</mainScreenCards>
<successScreen>
<enabled>true</enabled>
<limit>2147483647</limit>
<backendTipsBroker>true</backendTipsBroker>
</successScreen>
<mainScreenStories>
<enabled>true</enabled>
<limit>2147483647</limit>
<closed>false</closed>
<opened>false</opened>
<backendTipsBroker>false</backendTipsBroker>
<title>Рекомендуем</title>
<no_offers_text>
Для вас пока нет рекомендаций, но они скоро появятся
</no_offers_text>
<preloadCount>1</preloadCount>
<lifetimeOfCache>5</lifetimeOfCache>
<cache>true</cache>
<lifetimeOfCachePermissions>2</lifetimeOfCachePermissions>
<cachePermissions>true</cachePermissions>
</mainScreenStories>
<mainScreenTutorial>
<enabled>true</enabled>
<limit>10</limit>
<backendTipsBroker>false</backendTipsBroker>
</mainScreenTutorial>
<paymentsHistoryScreen>
<enabled>true</enabled>
<limit>1</limit>
<formNames>
<formName>ExtCardTransferIn</formName>
<formName>ExtCardOtherIn</formName>
<formName>ExtCardCashIn</formName>
</formNames>
<minSumRUB>500</minSumRUB>
<maxSumRUB>100000000</maxSumRUB>
<termDays>365</termDays>
<backendTipsBroker>true</backendTipsBroker>
</paymentsHistoryScreen>
</node>
<node id="node1.online.sberbank.ru">
<enabled>true</enabled>
<settings>
<cache>
<lifetimeOfIcons>129600</lifetimeOfIcons>
<lifetimeOfImages>20160</lifetimeOfImages>
</cache>
</settings>
<mainScreen>
<enabled>true</enabled>
<limit>2147483647</limit>
<closed>true</closed>
<opened>false</opened>
<backendTipsBroker>true</backendTipsBroker>
</mainScreen>
<mainScreenDeposits>
<enabled>true</enabled>
<limit>1</limit>
</mainScreenDeposits>
<mainScreenLoans>
<enabled>true</enabled>
<limit>1</limit>
</mainScreenLoans>
<mainScreenCards>
<enabled>true</enabled>
<limit>1</limit>
</mainScreenCards>
<successScreen>
<enabled>true</enabled>
<limit>2147483647</limit>
<backendTipsBroker>false</backendTipsBroker>
</successScreen>
<mainScreenStories>
<enabled>true</enabled>
<limit>2147483647</limit>
<closed>false</closed>
<opened>false</opened>
<backendTipsBroker>false</backendTipsBroker>
<title>Рекомендуем</title>
<no_offers_text>
Для вас пока нет рекомендаций, но они скоро появятся
</no_offers_text>
<preloadCount>1</preloadCount>
<lifetimeOfCache>5</lifetimeOfCache>
<cache>true</cache>
<lifetimeOfCachePermissions>2</lifetimeOfCachePermissions>
<cachePermissions>true</cachePermissions>
</mainScreenStories>
<mainScreenTutorial>
<enabled>true</enabled>
<limit>10</limit>
<backendTipsBroker>false</backendTipsBroker>
</mainScreenTutorial>
<paymentsHistoryScreen>
<enabled>true</enabled>
<limit>1</limit>
<formNames>
<formName>ExtCardTransferIn</formName>
<formName>ExtCardOtherIn</formName>
<formName>ExtCardCashIn</formName>
</formNames>
<minSumRUB>500</minSumRUB>
<maxSumRUB>100000000</maxSumRUB>
<termDays>365</termDays>
<backendTipsBroker>true</backendTipsBroker>
</paymentsHistoryScreen>
</node>
<node id="node2.online.sberbank.ru">
<enabled>true</enabled>
<settings>
<cache>
<lifetimeOfIcons>129600</lifetimeOfIcons>
<lifetimeOfImages>20160</lifetimeOfImages>
</cache>
</settings>
<mainScreen>
<enabled>true</enabled>
<limit>2147483647</limit>
<closed>true</closed>
<opened>false</opened>
<backendTipsBroker>true</backendTipsBroker>
</mainScreen>
<mainScreenDeposits>
<enabled>true</enabled>
<limit>1</limit>
</mainScreenDeposits>
<mainScreenLoans>
<enabled>true</enabled>
<limit>1</limit>
</mainScreenLoans>
<mainScreenCards>
<enabled>true</enabled>
<limit>1</limit>
</mainScreenCards>
<successScreen>
<enabled>true</enabled>
<limit>2147483647</limit>
<backendTipsBroker>true</backendTipsBroker>
</successScreen>
<mainScreenStories>
<enabled>true</enabled>
<limit>2147483647</limit>
<closed>false</closed>
<opened>false</opened>
<backendTipsBroker>false</backendTipsBroker>
<title>Рекомендуем</title>
<no_offers_text>
Для вас пока нет рекомендаций, но они скоро появятся
</no_offers_text>
<preloadCount>1</preloadCount>
<lifetimeOfCache>5</lifetimeOfCache>
<cache>true</cache>
<lifetimeOfCachePermissions>2</lifetimeOfCachePermissions>
<cachePermissions>true</cachePermissions>
</mainScreenStories>
<mainScreenTutorial>
<enabled>true</enabled>
<limit>10</limit>
<backendTipsBroker>false</backendTipsBroker>
</mainScreenTutorial>
<paymentsHistoryScreen>
<enabled>true</enabled>
<limit>1</limit>
<formNames>
<formName>ExtCardTransferIn</formName>
<formName>ExtCardOtherIn</formName>
<formName>ExtCardCashIn</formName>
</formNames>
<minSumRUB>500</minSumRUB>
<maxSumRUB>100000000</maxSumRUB>
<termDays>365</termDays>
<backendTipsBroker>true</backendTipsBroker>
</paymentsHistoryScreen>
</node>
<node id="node3.online.sberbank.ru">
<enabled>true</enabled>
<settings>
<cache>
<lifetimeOfIcons>129600</lifetimeOfIcons>
<lifetimeOfImages>20160</lifetimeOfImages>
</cache>
</settings>
<mainScreen>
<enabled>true</enabled>
<limit>2147483647</limit>
<closed>true</closed>
<opened>false</opened>
<backendTipsBroker>true</backendTipsBroker>
</mainScreen>
<mainScreenDeposits>
<enabled>true</enabled>
<limit>1</limit>
</mainScreenDeposits>
<mainScreenLoans>
<enabled>true</enabled>
<limit>1</limit>
</mainScreenLoans>
<mainScreenCards>
<enabled>true</enabled>
<limit>1</limit>
</mainScreenCards>
<successScreen>
<enabled>true</enabled>
<limit>2147483647</limit>
<backendTipsBroker>true</backendTipsBroker>
</successScreen>
<mainScreenStories>
<enabled>true</enabled>
<limit>2147483647</limit>
<closed>false</closed>
<opened>false</opened>
<backendTipsBroker>false</backendTipsBroker>
<title>Рекомендуем</title>
<no_offers_text>
Для вас пока нет рекомендаций, но они скоро появятся
</no_offers_text>
<preloadCount>1</preloadCount>
<lifetimeOfCache>5</lifetimeOfCache>
<cache>true</cache>
<lifetimeOfCachePermissions>2</lifetimeOfCachePermissions>
<cachePermissions>true</cachePermissions>
</mainScreenStories>
<mainScreenTutorial>
<enabled>true</enabled>
<limit>10</limit>
<backendTipsBroker>false</backendTipsBroker>
</mainScreenTutorial>
<paymentsHistoryScreen>
<enabled>true</enabled>
<limit>1</limit>
<formNames>
<formName>ExtCardTransferIn</formName>
<formName>ExtCardOtherIn</formName>
<formName>ExtCardCashIn</formName>
</formNames>
<minSumRUB>500</minSumRUB>
<maxSumRUB>100000000</maxSumRUB>
<termDays>365</termDays>
<backendTipsBroker>true</backendTipsBroker>
</paymentsHistoryScreen>
</node>
<node id="node4.online.sberbank.ru">
<enabled>true</enabled>
<settings>
<cache>
<lifetimeOfIcons>129600</lifetimeOfIcons>
<lifetimeOfImages>20160</lifetimeOfImages>
</cache>
</settings>
<mainScreen>
<enabled>true</enabled>
<limit>2147483647</limit>
<closed>true</closed>
<opened>false</opened>
<backendTipsBroker>true</backendTipsBroker>
</mainScreen>
<mainScreenDeposits>
<enabled>true</enabled>
<limit>1</limit>
</mainScreenDeposits>
<mainScreenLoans>
<enabled>true</enabled>
<limit>1</limit>
</mainScreenLoans>
<mainScreenCards>
<enabled>true</enabled>
<limit>1</limit>
</mainScreenCards>
<successScreen>
<enabled>true</enabled>
<limit>2147483647</limit>
<backendTipsBroker>true</backendTipsBroker>
</successScreen>
<mainScreenStories>
<enabled>true</enabled>
<limit>2147483647</limit>
<closed>false</closed>
<opened>false</opened>
<title>Рекомендуем</title>
<no_offers_text>
Для вас пока нет рекомендаций, но они скоро появятся
</no_offers_text>
<preloadCount>1</preloadCount>
<backendTipsBroker>false</backendTipsBroker>
<lifetimeOfCache>5</lifetimeOfCache>
<cache>true</cache>
<lifetimeOfCachePermissions>2</lifetimeOfCachePermissions>
<cachePermissions>true</cachePermissions>
</mainScreenStories>
<mainScreenTutorial>
<enabled>true</enabled>
<limit>10</limit>
<backendTipsBroker>false</backendTipsBroker>
</mainScreenTutorial>
<paymentsHistoryScreen>
<enabled>true</enabled>
<limit>1</limit>
<formNames>
<formName>ExtCardTransferIn</formName>
<formName>ExtCardOtherIn</formName>
<formName>ExtCardCashIn</formName>
</formNames>
<minSumRUB>500</minSumRUB>
<maxSumRUB>100000000</maxSumRUB>
<termDays>365</termDays>
<backendTipsBroker>true</backendTipsBroker>
</paymentsHistoryScreen>
</node>
</nodes>
</param>
<param name="CardRegistrationApp" description="Включение регистрации устройства по номеру карты">
<type>setting</type>
<enabled>true</enabled>
</param>
<param name="LoginBirthdayRegistrationApp" description="Включение регистрации по логину и дате рождения">
<type>setting</type>
<enabled>true</enabled>
</param>
<param name="digitalCreditCustomers" description="Список серверов, за которыми закреплены клиенты, которым доступен конкретный функционал">
<type>list</type>
<enabled>true</enabled>
<versions>
<version id="9.3">
<loanRequest>false</loanRequest>
<insuranceOnIssuance>false</insuranceOnIssuance>
<mainDeeplink>false</mainDeeplink>
</version>
<version id="9.4">
<loanRequest>false</loanRequest>
<insuranceOnIssuance>false</insuranceOnIssuance>
<mainDeeplink>false</mainDeeplink>
</version>
<version id="9.4.1">
<loanRequest>false</loanRequest>
<insuranceOnIssuance>false</insuranceOnIssuance>
<mainDeeplink>false</mainDeeplink>
</version>
<version id="9.5">
<loanRequest>false</loanRequest>
<insuranceOnIssuance>false</insuranceOnIssuance>
<mainDeeplink>false</mainDeeplink>
</version>
<version id="9.6">
<loanRequest>true</loanRequest>
<insuranceOnIssuance>true</insuranceOnIssuance>
<mainDeeplink>true</mainDeeplink>
</version>
<version id="default">
<loanRequest>true</loanRequest>
<insuranceOnIssuance>true</insuranceOnIssuance>
<mainDeeplink>true</mainDeeplink>
<loanRequestPreadopted>true</loanRequestPreadopted>
</version>
</versions>
</param>
<param name="digitalCreditServices" description="Параметры сервисов функционала">
<type>list</type>
<enabled>true</enabled>
<services>
<service name="ufs.consumer.loan.v1" description="Сервис ЕФС">
<host/>
<path>
consumer-loan/v2/mobile/banking/products/loans/consumerloan/request
</path>
</service>
<service name="PersData" description="Текст виджета условий обработки ПДн">
<host>https://185.157.96.21:443</host>
<path>
consumer-loan/v2/mobile/banking/products/loans/consumerloan/request/GetConfirmationAgreement/
</path>
</service>
<service name="restForMain.v1">
<host/>
<path>
consumer-loan/v1/mobile/banking/products/loans/requests/list
</path>
</service>
<service name="deeplinkToMainFlow">
<version id="default">
<flow permission="UFSLoanRequestPreadopted">doActionPreadopted</flow>
<flow permission="UFSLoanRequestWithInsurance">doActionWithInsuranceDeepLink</flow>
<flow permission="UFSLoanRequest">doActionDeepLink</flow>
</version>
</service>
</services>
</param>
<param name="CoreAddress" description="Адрес хоста и путь к веб сервису КЛАДР">
<type>service</type>
<enabled>true</enabled>
<services>
<service name="ufs.kladr.v1">
<host>https://185.157.96.21:443</host>
<path>
/loan-suggestion/services/rest/v2/SBOL/Suggestions.KLADR
</path>
</service>
<service name="ufs.kladr.v2">
<host>https://ift.testefs.sberbank.ru/</host>
<path>
/loan-suggestion/services/rest/v2/mobile/Suggestions.KLADR
</path>
</service>
<service name="ufs7.kladr.v1">
<host>
https://nginx-ios.ift-node5.testonline.sberbank.ru/
</host>
<path>/loan-suggestion/services/rs/Suggestions.KLADR</path>
</service>
</services>
</param>
<param name="shouldShowCreditCapacityScale" description="Отображение шкалы кредитного потенциала в процессе оформления кредитной карты">
<type>service</type>
<enabled>true</enabled>
</param>
<param name="creditCardOrder" description="Заказ кредитной карты в ЕФС">
<type>service</type>
<enabled>true</enabled>
</param>
<param name="creditCardOrderV2" description="Заказ кредитной карты в ЕФС, версия 2">
<type>service</type>
<enabled>true</enabled>
</param>
<param name="digitalCreditCardOrder" description="Заказ цифровой кредитной карты в ЕФС">
<type>service</type>
<enabled>true</enabled>
</param>
<param name="creditCardDynamicFields" description="Динамические поля на экране с информацией по кредитной карте при заказе в ЕФС">
<type>service</type>
<enabled>true</enabled>
</param>
<param name="creditCardUfsHistory" description="Отображение подробностей по заказу кредитной карты ЕФС в ИО">
<type>service</type>
<enabled>true</enabled>
</param>
<param name="creditCardOrderServices" description="Параметры сервисов функционала заказа кредитной карты в ЕФС">
<type>list</type>
<enabled>true</enabled>
<services>
<service name="persDataAgreement" description="Текст виджета условий обработки персональных данных">
<host>https://pfl-psi.efstst.sigma.sbrf.ru:443</host>
<path>
/credit-cards/short-form-capacity/v1/mobile/banking/product/ccard/short-ccard-request/getTextOfAgreementOnTransferInfo
</path>
</service>
</services>
</param>
<param name="PushPlatformID" description="URL серверов Push-платформы">
<type>setting</type>
<enabled>true</enabled>
<platforms>
<platform id="1" url="http://pushservertest.mfms.ru/push-test"/>
<platform id="3" url="https://pushserver.mfms.ru/sbrf"/>
<platform id="4" url="https://pushserver.sberbank-tele.com"/>
<platform id="5" url="https://pushserver-test.sberbank-tele.com"/>
</platforms>
</param>
<param name="StatementsAndReferencesEntryPoint" description="Справки и выписки c v9.3 и более">
<type>list</type>
<enabled>true</enabled>
<old_entry>true</old_entry>
<nodes>
<node id="node0.online.sberbank.ru">
<enabled>true</enabled>
<statementsHistory>true</statementsHistory>
<old_entry>true</old_entry>
<statementsSmartSearch>true</statementsSmartSearch>
<statementsPeriodLimit>true</statementsPeriodLimit>
</node>
<node id="node1.online.sberbank.ru">
<enabled>true</enabled>
<statementsHistory>true</statementsHistory>
<old_entry>true</old_entry>
<statementsSmartSearch>true</statementsSmartSearch>
<statementsPeriodLimit>true</statementsPeriodLimit>
</node>
<node id="node2.online.sberbank.ru">
<enabled>true</enabled>
<statementsHistory>true</statementsHistory>
<old_entry>true</old_entry>
<statementsSmartSearch>true</statementsSmartSearch>
<statementsPeriodLimit>true</statementsPeriodLimit>
</node>
<node id="node3.online.sberbank.ru">
<enabled>true</enabled>
<statementsHistory>true</statementsHistory>
<old_entry>true</old_entry>
<statementsSmartSearch>true</statementsSmartSearch>
<statementsPeriodLimit>true</statementsPeriodLimit>
</node>
<node id="greenfield1.online.sberbank.ru">
<enabled>true</enabled>
<statementsHistory>true</statementsHistory>
<old_entry>true</old_entry>
<statementsSmartSearch>true</statementsSmartSearch>
<statementsPeriodLimit>true</statementsPeriodLimit>
</node>
<node id="greenfield2.online.sberbank.ru">
<enabled>false</enabled>
<statementsHistory>true</statementsHistory>
<old_entry>true</old_entry>
<statementsSmartSearch>true</statementsSmartSearch>
<statementsPeriodLimit>true</statementsPeriodLimit>
</node>
<node id="mobile.sberbank.ru">
<enabled>true</enabled>
<statementsHistory>true</statementsHistory>
<old_entry>true</old_entry>
<statementsSmartSearch>true</statementsSmartSearch>
<statementsPeriodLimit>true</statementsPeriodLimit>
</node>
<node id="ift-node1.testonline.sberbank.ru">
<enabled>true</enabled>
<statementsHistory>false</statementsHistory>
<old_entry>true</old_entry>
<statementsSmartSearch>true</statementsSmartSearch>
<statementsPeriodLimit>true</statementsPeriodLimit>
</node>
<node id="ift-node2.testonline.sberbank.ru">
<enabled>true</enabled>
<statementsHistory>false</statementsHistory>
<old_entry>true</old_entry>
<statementsSmartSearch>true</statementsSmartSearch>
<statementsPeriodLimit>true</statementsPeriodLimit>
</node>
<node id="ift-node1-mp.testonline.sberbank.ru">
<enabled>true</enabled>
<statementsHistory>true</statementsHistory>
<old_entry>true</old_entry>
<statementsSmartSearch>true</statementsSmartSearch>
<statementsPeriodLimit>true</statementsPeriodLimit>
</node>
<node id="ift-node2-mp.testonline.sberbank.ru">
<enabled>true</enabled>
<statementsHistory>true</statementsHistory>
<old_entry>true</old_entry>
<statementsSmartSearch>true</statementsSmartSearch>
<statementsPeriodLimit>true</statementsPeriodLimit>
</node>
<node id="ift-node5-mp.testonline.sberbank.ru">
<enabled>true</enabled>
<statementsHistory>true</statementsHistory>
<old_entry>true</old_entry>
<statementsSmartSearch>true</statementsSmartSearch>
<statementsPeriodLimit>true</statementsPeriodLimit>
</node>
</nodes>
</param>
<param name="StatementsAndReferences" description="Справки и выписки c v8.11">
<type>list</type>
<nodes>
<node id="node0.online.sberbank.ru">
<statementsHistory>true</statementsHistory>
</node>
<node id="node1.online.sberbank.ru">
<statementsHistory>true</statementsHistory>
</node>
<node id="node2.online.sberbank.ru">
<statementsHistory>true</statementsHistory>
</node>
<node id="node3.online.sberbank.ru">
<statementsHistory>true</statementsHistory>
</node>
<node id="greenfield1.online.sberbank.ru">
<statementsHistory>true</statementsHistory>
</node>
<node id="greenfield2.online.sberbank.ru">
<statementsHistory>true</statementsHistory>
</node>
<node id="mobile.sberbank.ru">
<statementsHistory>true</statementsHistory>
</node>
<node id="ift-node1.testonline.sberbank.ru">
<statementsHistory>true</statementsHistory>
</node>
<node id="ift-node2.testonline.sberbank.ru">
<statementsHistory>true</statementsHistory>
</node>
<node id="ift-node1-mp.testonline.sberbank.ru">
<statementsHistory>true</statementsHistory>
</node>
<node id="ift-node2-mp.testonline.sberbank.ru">
<statementsHistory>true</statementsHistory>
</node>
</nodes>
</param>
<param name="StaticSourceMerchantPics" description="статресурс для логотипов">
<type>source</type>
<link>https://pfm-stat.online.sberbank.ru/PFM/logos/</link>
</param>
<param name="CarLoanRequest" description="Заявка на автокредит с версии 9.3">
<type>setting</type>
<enabled>true</enabled>
</param>
<param name="CarLoan" description="Заявка на автокредит">
<type>setting</type>
<enabled>false</enabled>
</param>
<param name="CarLoansOperationHistory" description="Работа с историей операций">
<type>setting</type>
<enabled>true</enabled>
</param>
<param name="CarLoansDetails2" description="Детализация автокредита">
<type>setting</type>
<enabled>true</enabled>
</param>
<param name="CarLoansPayment" description="Пополнение счета по автокредиту">
<type>setting</type>
<enabled>true</enabled>
<refillProvider>623065</refillProvider>
<param name="CarLoansDeeplink" description="Диплинк">
<type>setting</type>
<enabled>true</enabled>
</param>
</param>
<param name="CarLoansTutorial" description="Отображение туториала">
<type>setting</type>
<enabled>true</enabled>
</param>
<param name="CarLoansRus" description="Ввод марок/моделей на русском">
<type>setting</type>
<enabled>true</enabled>
</param>
<param name="CarLoanServices" description="Параметры сервисов функционала">
<type>list</type>
<enabled>true</enabled>
<services>
<service name="PersData" description="Текст виджета условий обработки ПДн">
<host>https://ift.testefs.sberbank.ru/</host>
<path>
/person-credit-mb/v1/mobile/Banking/Products/Loans/CarLoans/Application/GetAgreement
</path>
</service>
</services>
</param>
<param name="WelfareProductsMainScreen" description="Продукты благосостояния на главном экране">
<type>setting</type>
<enabled>true</enabled>
</param>
<param name="WelfareTutorial" description="Туториал на фичу">
<type>setting</type>
<enabled>true</enabled>
</param>
<param name="WelfareProductsDetails" description="Карточки продуктов благосостояния (детализация продукта)">
<type>setting</type>
<enabled>true</enabled>
</param>
<param name="welfareProducts" description="Продукты благосостояния">
<type>list</type>
<enabled>true</enabled>
<nodes>
<node id="greenfield1.online.sberbank.ru">
<isShowInFinance>true</isShowInFinance>
<isShowInFinancev2>true</isShowInFinancev2>
<actionInvestmentsBuy>true</actionInvestmentsBuy>
<actionPIF>true</actionPIF>
<actionIPP>true</actionIPP>
<autopaymentIPP>true</autopaymentIPP>
</node>
<node id="194.186.207.23">
<isShowInFinance>true</isShowInFinance>
<isShowInFinancev2>true</isShowInFinancev2>
<actionInvestmentsBuy>true</actionInvestmentsBuy>
<actionPIF>true</actionPIF>
<actionIPP>true</actionIPP>
<autopaymentIPP>true</autopaymentIPP>
</node>
<node id="mobile.sberbank.ru">
<isShowInFinance>true</isShowInFinance>
<isShowInFinancev2>true</isShowInFinancev2>
<actionInvestmentsBuy>true</actionInvestmentsBuy>
<actionPIF>true</actionPIF>
<actionIPP>true</actionIPP>
<autopaymentIPP>true</autopaymentIPP>
</node>
<node id="node0.online.sberbank.ru">
<isShowInFinance>true</isShowInFinance>
<isShowInFinancev2>true</isShowInFinancev2>
<actionInvestmentsBuy>true</actionInvestmentsBuy>
<actionPIF>true</actionPIF>
<autopaymentIPP>true</autopaymentIPP>
</node>
<node id="node1.online.sberbank.ru">
<isShowInFinance>true</isShowInFinance>
<isShowInFinancev2>true</isShowInFinancev2>
<actionInvestmentsBuy>true</actionInvestmentsBuy>
<actionPIF>true</actionPIF>
<autopaymentIPP>true</autopaymentIPP>
</node>
<node id="node2.online.sberbank.ru">
<isShowInFinance>true</isShowInFinance>
<isShowInFinancev2>true</isShowInFinancev2>
<actionInvestmentsBuy>true</actionInvestmentsBuy>
<actionPIF>true</actionPIF>
<actionIPP>true</actionIPP>
<autopaymentIPP>true</autopaymentIPP>
</node>
<node id="node3.online.sberbank.ru">
<isShowInFinance>true</isShowInFinance>
<isShowInFinancev2>true</isShowInFinancev2>
<actionInvestmentsBuy>true</actionInvestmentsBuy>
<actionPIF>true</actionPIF>
<actionIPP>true</actionIPP>
<autopaymentIPP>true</autopaymentIPP>
</node>
<node id="ift-node1.testonline.sberbank.ru">
<isShowInFinance>true</isShowInFinance>
<isShowInFinancev2>true</isShowInFinancev2>
<actionInvestmentsBuy>true</actionInvestmentsBuy>
<actionPIF>true</actionPIF>
<actionIPP>true</actionIPP>
<autopaymentIPP>true</autopaymentIPP>
</node>
<node id="ift-node2.testonline.sberbank.ru">
<isShowInFinance>true</isShowInFinance>
<isShowInFinancev2>true</isShowInFinancev2>
<actionInvestmentsBuy>true</actionInvestmentsBuy>
<actionPIF>true</actionPIF>
<actionIPP>true</actionIPP>
<autopaymentIPP>true</autopaymentIPP>
</node>
<node id="ift-node5.testonline.sberbank.ru">
<isShowInFinance>true</isShowInFinance>
<isShowInFinancev2>true</isShowInFinancev2>
<actionInvestmentsBuy>true</actionInvestmentsBuy>
<actionPIF>true</actionPIF>
<actionIPP>true</actionIPP>
<autopaymentIPP>true</autopaymentIPP>
</node>
<node id="ift-node1-mp.testonline.sberbank.ru">
<isShowInFinance>true</isShowInFinance>
<isShowInFinancev2>true</isShowInFinancev2>
<actionInvestmentsBuy>true</actionInvestmentsBuy>
<actionPIF>true</actionPIF>
<actionIPP>true</actionIPP>
<autopaymentIPP>true</autopaymentIPP>
</node>
<node id="ift-node2-mp.testonline.sberbank.ru">
<isShowInFinance>true</isShowInFinance>
<isShowInFinancev2>true</isShowInFinancev2>
<actionInvestmentsBuy>true</actionInvestmentsBuy>
<actionPIF>true</actionPIF>
<actionIPP>true</actionIPP>
<autopaymentIPP>true</autopaymentIPP>
</node>
<node id="ift-node5-mp.testonline.sberbank.ru">
<isShowInFinance>true</isShowInFinance>
<isShowInFinancev2>true</isShowInFinancev2>
<actionInvestmentsBuy>true</actionInvestmentsBuy>
<actionPIF>true</actionPIF>
<actionIPP>true</actionIPP>
<autopaymentIPP>true</autopaymentIPP>
</node>
<node id="10.21.152.7">
<isShowInFinance>true</isShowInFinance>
<isShowInFinancev2>true</isShowInFinancev2>
<actionInvestmentsBuy>true</actionInvestmentsBuy>
<actionPIF>true</actionPIF>
<actionIPP>true</actionIPP>
<autopaymentIPP>true</autopaymentIPP>
</node>
<node id="msv-node2.testonline.sberbank.ru">
<isShowInFinance>true</isShowInFinance>
<isShowInFinancev2>true</isShowInFinancev2>
<actionInvestmentsBuy>true</actionInvestmentsBuy>
<actionPIF>true</actionPIF>
<actionIPP>true</actionIPP>
<autopaymentIPP>true</autopaymentIPP>
</node>
</nodes>
</param>
<param name="ContractListv2.1" description="Версия сервиса ContractList 2.1">
<type>setting</type>
<enabled>false</enabled>
</param>
<param name="UfsInsuranceMain" description="Отображение действующих страховых полисов на главной">
<type>setting</type>
<enabled>true</enabled>
</param>
<param name="UfsInsuranceMainContractsDetails" description="Отображение детальной информации по действующим страховым полисам на главной">
<type>setting</type>
<enabled>true</enabled>
</param>
<param name="UfsInsuranceMainTurorial" description="Отображение туториала по страховкам">
<type>setting</type>
<enabled>true</enabled>
</param>
<param name="UfsInsuranceContracts" description="Список страховых контрактов и детальной информации по ним">
<type>setting</type>
<enabled>true</enabled>
</param>
<param name="UfsInvestmentsBuyShareHistory" description="История операций по докупке ПИФ">
<type>setting</type>
<enabled>true</enabled>
</param>
<param name="UfsPensionPaymentIppHistory" description="История операций по пополнению ИПП">
<type>setting</type>
<enabled>true</enabled>
</param>
<param name="UfsRurPayment" description="классические переводы в ЕФС, замена переводов ЕРИБа">
<type>service</type>
<enabled>true</enabled>
</param>
<param name="AccountSpecialCondition" description="Специальные условия по вкладу. Ограничение на максимальную сумму">
<type>setting</type>
<enabled>true</enabled>
</param>
<param name="AccountSpecialConditionSum" description="Максимальное значение первоначального взноса, с которого начинает действовать пониженный процент по вкладу">
<currencies>
<currency>
<id>RUB</id>
<maxamount>100000</maxamount>
</currency>
<currency>
<id>OTHER</id>
<maxamount>0</maxamount>
</currency>
</currencies>
</param>
<param name="UiCaseGibddPenaltySearch" description="Уникальный пользовательский сценарий для поиска штрафов по ВУ/СТС">
<type>list</type>
<nodes>
<node id="mobile.sberbank.ru">
<enabled>true</enabled>
<serviceID>688079</serviceID>
<targetService>688457</targetService>
<targetBilling>344</targetBilling>
<targetProvider>688457</targetProvider>
</node>
<node id="ift-node1.testonline.sberbank.ru">
<enabled>true</enabled>
<serviceID>624234</serviceID>
<targetService>623095</targetService>
<targetBilling>344</targetBilling>
<targetProvider>623095</targetProvider>
</node>
<node id="ift-node2.testonline.sberbank.ru">
<enabled>true</enabled>
<serviceID>623567</serviceID>
<targetService>621958</targetService>
<targetBilling>344</targetBilling>
<targetProvider>621958</targetProvider>
</node>
<node id="ift-node1-mp.testonline.sberbank.ru">
<enabled>true</enabled>
<serviceID>624234</serviceID>
<targetService>623095</targetService>
<targetBilling>344</targetBilling>
<targetProvider>623095</targetProvider>
</node>
<node id="ift-node2-mp.testonline.sberbank.ru">
<enabled>true</enabled>
<serviceID>623567</serviceID>
<targetService>621958</targetService>
<targetBilling>344</targetBilling>
<targetProvider>621958</targetProvider>
</node>
<node id="node3.online.sberbank.ru">
<enabled>true</enabled>
<serviceID>500202753</serviceID>
<targetService>500413146</targetService>
<targetBilling>284</targetBilling>
<targetProvider>500413146</targetProvider>
</node>
<node id="node2.online.sberbank.ru">
<enabled>true</enabled>
<serviceID>500204565</serviceID>
<targetService>500413943</targetService>
<targetBilling>284</targetBilling>
<targetProvider>500413943</targetProvider>
</node>
<node id="node1.online.sberbank.ru">
<enabled>true</enabled>
<serviceID>387491</serviceID>
<targetService>596879</targetService>
<targetBilling>284</targetBilling>
<targetProvider>596879</targetProvider>
</node>
<node id="greenfield1.online.sberbank.ru">
<enabled>true</enabled>
<serviceID>500202753</serviceID>
<targetService>550445849</targetService>
<targetBilling>284</targetBilling>
<targetProvider>550445849</targetProvider>
</node>
<node id="greenfield2.online.sberbank.ru">
<enabled>true</enabled>
<serviceID>500202753</serviceID>
<targetService>550445849</targetService>
<targetBilling>284</targetBilling>
<targetProvider>550445849</targetProvider>
</node>
</nodes>
</param>
<param name="UiCaseGibddPenaltyPayByUin" description="Уникальный пользовательский сценарий для оплаты штрафов по УИН">
<type>list</type>
<nodes>
<node id="mobile.sberbank.ru">
<enabled>false</enabled>
<serviceID>222222</serviceID>
<targetService>688092</targetService>
<targetBilling>344</targetBilling>
<targetProvider>688092</targetProvider>
</node>
<node id="ift-node1.testonline.sberbank.ru">
<enabled>false</enabled>
<serviceID>617948</serviceID>
<targetService>621822</targetService>
<targetBilling>344</targetBilling>
<targetProvider>621822</targetProvider>
</node>
<node id="ift-node2.testonline.sberbank.ru">
<enabled>false</enabled>
<serviceID>618120</serviceID>
<targetService>620678</targetService>
<targetBilling>344</targetBilling>
<targetProvider>620678</targetProvider>
</node>
<node id="ift-node1-mp.testonline.sberbank.ru">
<enabled>false</enabled>
<serviceID>617948</serviceID>
<targetService>621822</targetService>
<targetBilling>344</targetBilling>
<targetProvider>621822</targetProvider>
</node>
<node id="ift-node2-mp.testonline.sberbank.ru">
<enabled>false</enabled>
<serviceID>618120</serviceID>
<targetService>620678</targetService>
<targetBilling>344</targetBilling>
<targetProvider>620678</targetProvider>
</node>
</nodes>
</param>
<param name="creditCapacity" description="Кредитный потенциал">
<type>setting</type>
<enabled>true</enabled>
<services>
<service name="CapacityCalculationAgreement" description="Текст согласия клиента на обработку персональных данных для расчета КП">
<path>
/persDataAgreement/pdp-agreement/v1/CapacityCalculationAgreement.json
</path>
<description>
Нажимая кнопку "Рассчитать", вы соглашаетесь с условиями
<a>ПАО Сбербанк</a>
</description>
</service>
<service name="CapacityConsumerRequestAgreement" description="Текст согласия клиента на подачу заявки на потребительский кредит">
<path>
/persDataAgreement/pdp-agreement/v1/CapacityConsumerRequestAgreement.json
</path>
<description>
Нажимая кнопку "Оформить", вы соглашаетесь с условиями
<a>ПАО Сбербанк</a>
</description>
</service>
</services>
<nodes>
<node id="node0.online.sberbank.ru">
<enabled>true</enabled>
<enabled_v2>true</enabled_v2>
<calculateCC>true</calculateCC>
<showcase>true</showcase>
<createCreditIssue>true</createCreditIssue>
<creditCardApplication>true</creditCardApplication>
<CCTutorial>true</CCTutorial>
<CCOperationHistory>true</CCOperationHistory>
</node>
<node id="node1.online.sberbank.ru">
<enabled>true</enabled>
<enabled_v2>true</enabled_v2>
<calculateCC>true</calculateCC>
<showcase>true</showcase>
<createCreditIssue>true</createCreditIssue>
<creditCardApplication>true</creditCardApplication>
<CCTutorial>true</CCTutorial>
<CCOperationHistory>true</CCOperationHistory>
</node>
<node id="node2.online.sberbank.ru">
<enabled>true</enabled>
<enabled_v2>true</enabled_v2>
<calculateCC>true</calculateCC>
<showcase>true</showcase>
<createCreditIssue>true</createCreditIssue>
<creditCardApplication>true</creditCardApplication>
<CCTutorial>true</CCTutorial>
<CCOperationHistory>true</CCOperationHistory>
</node>
<node id="node3.online.sberbank.ru">
<enabled>true</enabled>
<enabled_v2>true</enabled_v2>
<calculateCC>true</calculateCC>
<showcase>true</showcase>
<createCreditIssue>true</createCreditIssue>
<creditCardApplication>true</creditCardApplication>
<CCTutorial>true</CCTutorial>
<CCOperationHistory>true</CCOperationHistory>
</node>
<node id="greenfield1.online.sberbank.ru">
<enabled>true</enabled>
<enabled_v2>true</enabled_v2>
<calculateCC>true</calculateCC>
<createCreditIssue>true</createCreditIssue>
<creditCardApplication>true</creditCardApplication>
<CCTutorial>true</CCTutorial>
<CCOperationHistory>false</CCOperationHistory>
</node>
<node id="greenfield2.online.sberbank.ru">
<enabled>true</enabled>
<enabled_v2>true</enabled_v2>
<calculateCC>true</calculateCC>
<showcase>true</showcase>
<createCreditIssue>true</createCreditIssue>
<creditCardApplication>true</creditCardApplication>
<CCTutorial>true</CCTutorial>
<CCOperationHistory>true</CCOperationHistory>
</node>
<node id="194.186.207.23">
<enabled>true</enabled>
<enabled_v2>true</enabled_v2>
<calculateCC>true</calculateCC>
<showcase>true</showcase>
<createCreditIssue>true</createCreditIssue>
<creditCardApplication>true</creditCardApplication>
<CCTutorial>true</CCTutorial>
<CCOperationHistory>true</CCOperationHistory>
</node>
<node id="mobile.sberbank.ru">
<enabled>true</enabled>
<enabled_v2>true</enabled_v2>
<calculateCC>true</calculateCC>
<showcase>true</showcase>
<createCreditIssue>true</createCreditIssue>
<creditCardApplication>true</creditCardApplication>
<CCTutorial>true</CCTutorial>
<CCOperationHistory>true</CCOperationHistory>
</node>
<node id="ift-node1.testonline.sberbank.ru">
<enabled>true</enabled>
<enabled_v2>true</enabled_v2>
<calculateCC>true</calculateCC>
<showcase>true</showcase>
<createCreditIssue>true</createCreditIssue>
<creditCardApplication>true</creditCardApplication>
<CCTutorial>true</CCTutorial>
<CCOperationHistory>true</CCOperationHistory>
</node>
<node id="ift-node2.testonline.sberbank.ru">
<enabled>true</enabled>
<enabled_v2>true</enabled_v2>
<calculateCC>true</calculateCC>
<showcase>true</showcase>
<createCreditIssue>true</createCreditIssue>
<creditCardApplication>true</creditCardApplication>
<CCTutorial>true</CCTutorial>
<CCOperationHistory>true</CCOperationHistory>
</node>
<node id="ift-node1-mp.testonline.sberbank.ru">
<enabled>true</enabled>
<enabled_v2>true</enabled_v2>
<calculateCC>true</calculateCC>
<showcase>true</showcase>
<createCreditIssue>true</createCreditIssue>
<creditCardApplication>true</creditCardApplication>
<CCTutorial>true</CCTutorial>
<CCOperationHistory>true</CCOperationHistory>
</node>
<node id="ift-node2-mp.testonline.sberbank.ru">
<enabled>true</enabled>
<enabled_v2>true</enabled_v2>
<calculateCC>true</calculateCC>
<showcase>true</showcase>
<createCreditIssue>true</createCreditIssue>
<creditCardApplication>true</creditCardApplication>
<CCTutorial>true</CCTutorial>
<CCOperationHistory>true</CCOperationHistory>
</node>
<node id="10.21.152.7">
<enabled>true</enabled>
<enabled_v2>true</enabled_v2>
<calculateCC>true</calculateCC>
<showcase>true</showcase>
<createCreditIssue>true</createCreditIssue>
<creditCardApplication>true</creditCardApplication>
<CCTutorial>true</CCTutorial>
<CCOperationHistory>true</CCOperationHistory>
</node>
</nodes>
</param>
<param name="mobilePOS" description="Интернет кредитование">
<POSVersions>
<version id="9.8">
<enabled>true</enabled>
<loanCalculator>true</loanCalculator>
<newStatusRoad>true</newStatusRoad>
</version>
<version id="9.7">
<enabled>true</enabled>
<loanCalculator>true</loanCalculator>
<newStatusRoad>false</newStatusRoad>
</version>
<version id="9.6">
<enabled>true</enabled>
<loanCalculator>true</loanCalculator>
<newStatusRoad>false</newStatusRoad>
</version>
<version id="default">
<enabled>true</enabled>
<loanCalculator>false</loanCalculator>
<newStatusRoad>false</newStatusRoad>
</version>
</POSVersions>
</param>
<param name="creditCapacity_v2" description="Кредитный потенциал v9.5 и выше">
<services>
<service name="CapacityCalculationAgreement" description="Текст согласия клиента на обработку персональных данных для расчета КП">
<path>
/persDataAgreement/pdp-agreement/v1/CapacityCalculationAgreement.json
</path>
</service>
<service name="CapacityConsumerRequestAgreement" description="Текст согласия клиента на подачу заявки на потребительский кредит">
<path>
/persDataAgreement/pdp-agreement/v1/CapacityConsumerRequestAgreement.json
</path>
</service>
</services>
<CCVersions>
<version id="9.7">
<enabled>true</enabled>
<calculateCC>true</calculateCC>
<showcase>true</showcase>
<loanApplication>true</loanApplication>
<creditCardApplication>true</creditCardApplication>
<CCTutorial>true</CCTutorial>
<CCOperationHistory>true</CCOperationHistory>
<calculateCCDeeplink>true</calculateCCDeeplink>
<showcaseDeeplink>true</showcaseDeeplink>
</version>
<version id="9.6">
<enabled>true</enabled>
<calculateCC>true</calculateCC>
<showcase>true</showcase>
<loanApplication>true</loanApplication>
<creditCardApplication>true</creditCardApplication>
<CCTutorial>true</CCTutorial>
<CCOperationHistory>true</CCOperationHistory>
<calculateCCDeeplink>true</calculateCCDeeplink>
<showcaseDeeplink>true</showcaseDeeplink>
</version>
<version id="9.5">
<enabled>true</enabled>
<calculateCC>true</calculateCC>
<showcase>true</showcase>
<loanApplication>true</loanApplication>
<creditCardApplication>true</creditCardApplication>
<CCTutorial>true</CCTutorial>
<CCOperationHistory>true</CCOperationHistory>
<calculateCCDeeplink>true</calculateCCDeeplink>
<showcaseDeeplink>true</showcaseDeeplink>
</version>
<version id="default">
<enabled>false</enabled>
<calculateCC>true</calculateCC>
<showcase>true</showcase>
<loanApplication>true</loanApplication>
<creditCardApplication>true</creditCardApplication>
<CCTutorial>true</CCTutorial>
<CCOperationHistory>true</CCOperationHistory>
<calculateCCDeeplink>true</calculateCCDeeplink>
<showcaseDeeplink>true</showcaseDeeplink>
<flowVersions>
<flowName name="form" version="1"/>
<flowName name="loanRequest" version="0"/>
<flowName name="operationHistory" version="0"/>
<flowName name="default" version="0"/>
</flowVersions>
</version>
</CCVersions>
</param>
<param name="ExternalLogin" description="Включение аутентификации через СБОЛ на внешних ресурсах">
<type>setting</type>
<enabled>false</enabled>
</param>
<param name="ExternalLogin_v2" description="Включение аутентификации через СБОЛ на внешних ресурсах v8.9.1+">
<type>setting</type>
<enabled>true</enabled>
</param>
<param name="ExternalLoginPKCE" description="Включение входа через SBOL с использованием спецификации PKCE">
<type>setting</type>
<enabled>true</enabled>
</param>
<param name="SberIdSeamlessAuth" description="Включение функционала бесшовной аутентификации через СБОЛ">
<type>setting</type>
<enabled>true</enabled>
</param>
<param name="SberIDNewClaims" description="Доработки по отображению списка передаваемых данных">
<type>setting</type>
<enabled>true</enabled>
</param>
<param name="SberIDReEntryFragment" description="Включение экрана повторного входа через SBOL">
<type>setting</type>
<enabled>false</enabled>
</param>
<param name="SberIdPaymentAndData" description="Включение оплаты/входа через SBOL">
<type>setting</type>
<enabled>true</enabled>
<string>
Сервис временно недоступен, приносим свои извинения.
</string>
</param>
<param name="P2PTransferByPhoneToOtherBank" description="Перевод в другие банки по номеру телефона через УЭК">
<type>list</type>
<enabled>true</enabled>
<CustomMessageLimitEnabled>true</CustomMessageLimitEnabled>
<CustomMessageLimit>
Обратите внимание! Доступный лимит для совершения операции составляет
</CustomMessageLimit>
<serviceProviders>
<serviceProvider name="Tinkoff" visibleName="Тинькофф Банк">
<nodes>
<node id="mobile.sberbank.ru">
<targetBilling>344</targetBilling>
<targetProvider>688468</targetProvider>
<targetService>688468</targetService>
</node>
<node id="ift-node1-mp.testonline.sberbank.ru">
<targetBilling>344</targetBilling>
<targetProvider>623368</targetProvider>
<targetService>623368</targetService>
</node>
<node id="ift-node2-mp.testonline.sberbank.ru">
<targetBilling>344</targetBilling>
<targetProvider>623368</targetProvider>
<targetService>623368</targetService>
</node>
<node id="greenfield1.online.sberbank.ru">
<targetBilling>284</targetBilling>
<targetProvider>550478249</targetProvider>
<targetService>550478249</targetService>
</node>
<node id="greenfield2.online.sberbank.ru">
<targetBilling>284</targetBilling>
<targetProvider>500439915</targetProvider>
<targetService>500439915</targetService>
</node>
<node id="node1.online.sberbank.ru">
<targetBilling>284</targetBilling>
<targetProvider>629175</targetProvider>
<targetService>629175</targetService>
</node>
<node id="node2.online.sberbank.ru">
<targetBilling>284</targetBilling>
<targetProvider>500446239</targetProvider>
<targetService>500446239</targetService>
</node>
<node id="node3.online.sberbank.ru">
<targetBilling>284</targetBilling>
<targetProvider>500445546</targetProvider>
<targetService>500445546</targetService>
</node>
<node id="node4.online.sberbank.ru">
<targetBilling>284</targetBilling>
<targetProvider>500439915</targetProvider>
<targetService>500439915</targetService>
</node>
</nodes>
</serviceProvider>
</serviceProviders>
</param>
<param name="ExternalTopUp" description="P2P Пополнение карты клиента с карты стороннего банка">
<type>service</type>
<enabled>true</enabled>
<nodes>
<node id="node0.online.sberbank.ru">
<enabled>true</enabled>
</node>
<node id="node1.online.sberbank.ru">
<enabled>true</enabled>
</node>
<node id="node2.online.sberbank.ru">
<enabled>true</enabled>
</node>
<node id="node3.online.sberbank.ru">
<enabled>true</enabled>
</node>
<node id="greenfield1.online.sberbank.ru">
<enabled>true</enabled>
</node>
<node id="mobile.sberbank.ru">
<enabled>true</enabled>
</node>
<node id="ift-node1.testonline.sberbank.ru">
<enabled>true</enabled>
</node>
<node id="ift-node2.testonline.sberbank.ru">
<enabled>true</enabled>
</node>
<node id="ift-node1-mp.testonline.sberbank.ru">
<enabled>true</enabled>
</node>
<node id="ift-node2-mp.testonline.sberbank.ru">
<enabled>true</enabled>
</node>
<node id="psinode2.testonline.sberbank.ru">
<enabled>true</enabled>
</node>
<node id="psinode1.testonline.sberbank.ru">
<enabled>true</enabled>
</node>
<node id="194.186.207.23">
<enabled>true</enabled>
</node>
</nodes>
</param>
<param name="P2PTransferByPhoneToOtherBankSKB" description="Перевод в Совкомбанк по номеру телефона через УЭК">
<type>list</type>
<enabled>true</enabled>
<serviceProviders>
<serviceProvider name="Sovcombank" visibleName="Совкомбанк">
<nodes>
<node id="ift-node1-mp.testonline.sberbank.ru">
<targetBilling>344</targetBilling>
<targetProvider>623438</targetProvider>
<targetService>623438</targetService>
</node>
<node id="ift-node2-mp.testonline.sberbank.ru">
<targetBilling>344</targetBilling>
<targetProvider>623438</targetProvider>
<targetService>623438</targetService>
</node>
<node id="mobile.sberbank.ru">
<targetBilling>344</targetBilling>
<targetProvider>688849</targetProvider>
<targetService>688849</targetService>
</node>
<node id="greenfield1.online.sberbank.ru">
<targetBilling>284</targetBilling>
<targetProvider>550478249</targetProvider>
<targetService>550478249</targetService>
</node>
<node id="greenfield2.online.sberbank.ru">
<targetBilling>284</targetBilling>
<targetProvider>500439915</targetProvider>
<targetService>500439915</targetService>
</node>
<node id="node1.online.sberbank.ru">
<targetBilling>284</targetBilling>
<targetProvider>629175</targetProvider>
<targetService>629175</targetService>
</node>
<node id="node2.online.sberbank.ru">
<targetBilling>284</targetBilling>
<targetProvider>500446239</targetProvider>
<targetService>500446239</targetService>
</node>
<node id="node3.online.sberbank.ru">
<targetBilling>284</targetBilling>
<targetProvider>500445546</targetProvider>
<targetService>500445546</targetService>
</node>
<node id="node4.online.sberbank.ru">
<targetBilling>284</targetBilling>
<targetProvider>500439915</targetProvider>
<targetService>500439915</targetService>
</node>
</nodes>
</serviceProvider>
</serviceProviders>
</param>
<param name="P2PTransferByPhoneToOtherBankGroupLayout" description="Группировка пунктов меню (банков) по секциям">
<type>setting</type>
<enabled>true</enabled>
</param>
<param name="P2PExternalBankTransfer2" description="Перевод в другой банк по номеру мобильного телефона">
<type>setting</type>
<enabled>true</enabled>
</param>
<param name="UsePushAutoDisable" description="активация алгоритма автоотключения push">
<type>setting</type>
<enabled>true</enabled>
</param>
<param name="brokerage_8_12" description="Брокерское обслуживание">
<enabled>true</enabled>
<replenishAccountEnabled>true</replenishAccountEnabled>
<replenishAccountInMarginCallEnabled>true</replenishAccountInMarginCallEnabled>
<createDocApplicationEnabled>true</createDocApplicationEnabled>
<brokerageHelpPhoneNumber>900</brokerageHelpPhoneNumber>
<brokerageProductsAvailableInFinance>true</brokerageProductsAvailableInFinance>
<brokerageFxWarningEnabled>true</brokerageFxWarningEnabled>
<nodes>
<node id="ift-node1.testonline.sberbank.ru">
<enabled>true</enabled>
<replenishAccountEnabled>true</replenishAccountEnabled>
<replenishAccountInMarginCallEnabled>true</replenishAccountInMarginCallEnabled>
<replenishAccountSearchString>Пополнение брокерского счета</replenishAccountSearchString>
<replenishAccountAgreementFieldCode>field(S85396525721A85396525552)</replenishAccountAgreementFieldCode>
<replenishAccountMarketFieldCode>field(S85396525721A85396525571)</replenishAccountMarketFieldCode>
<createDocApplicationEnabled>true</createDocApplicationEnabled>
<brokerageHelpPhoneNumber>900</brokerageHelpPhoneNumber>
<brokerageReplenishmentSelectionMarkets>true</brokerageReplenishmentSelectionMarkets>
</node>
<node id="ift-node2.testonline.sberbank.ru">
<enabled>true</enabled>
<replenishAccountEnabled>true</replenishAccountEnabled>
<replenishAccountInMarginCallEnabled>true</replenishAccountInMarginCallEnabled>
<replenishAccountSearchString>Пополнение брокерского счета</replenishAccountSearchString>
<replenishAccountAgreementFieldCode>field(S85396525721A85396525552)</replenishAccountAgreementFieldCode>
<replenishAccountMarketFieldCode>field(S85396525721A85396525571)</replenishAccountMarketFieldCode>
<createDocApplicationEnabled>true</createDocApplicationEnabled>
<brokerageHelpPhoneNumber>900</brokerageHelpPhoneNumber>
<brokerageReplenishmentSelectionMarkets>true</brokerageReplenishmentSelectionMarkets>
</node>
<node id="ift-node1-mp.testonline.sberbank.ru">
<enabled>true</enabled>
<replenishAccountEnabled>true</replenishAccountEnabled>
<replenishAccountInMarginCallEnabled>true</replenishAccountInMarginCallEnabled>
<replenishAccountSearchString>Пополнение брокерского счета</replenishAccountSearchString>
<replenishAccountAgreementFieldCode>field(S85396525721A85396525552)</replenishAccountAgreementFieldCode>
<replenishAccountMarketFieldCode>field(S85396525721A85396525571)</replenishAccountMarketFieldCode>
<createDocApplicationEnabled>true</createDocApplicationEnabled>
<brokerageHelpPhoneNumber>900</brokerageHelpPhoneNumber>
<brokerageReplenishmentSelectionMarkets>true</brokerageReplenishmentSelectionMarkets>
</node>
<node id="ift-node2-mp.testonline.sberbank.ru">
<enabled>true</enabled>
<replenishAccountEnabled>true</replenishAccountEnabled>
<replenishAccountInMarginCallEnabled>true</replenishAccountInMarginCallEnabled>
<replenishAccountSearchString>Пополнение брокерского счета</replenishAccountSearchString>
<replenishAccountAgreementFieldCode>field(S85396525721A85396525552)</replenishAccountAgreementFieldCode>
<replenishAccountMarketFieldCode>field(S85396525721A85396525571)</replenishAccountMarketFieldCode>
<createDocApplicationEnabled>true</createDocApplicationEnabled>
<brokerageHelpPhoneNumber>900</brokerageHelpPhoneNumber>
<brokerageReplenishmentSelectionMarkets>true</brokerageReplenishmentSelectionMarkets>
</node>
<node id="ift-node5-mp.testonline.sberbank.ru">
<enabled>true</enabled>
<replenishAccountEnabled>true</replenishAccountEnabled>
<replenishAccountInMarginCallEnabled>true</replenishAccountInMarginCallEnabled>
<replenishAccountSearchString>Пополнение брокерского счета</replenishAccountSearchString>
<replenishAccountAgreementFieldCode>field(S85396525721A85396525552)</replenishAccountAgreementFieldCode>
<replenishAccountMarketFieldCode>field(S85396525721A85396525571)</replenishAccountMarketFieldCode>
<createDocApplicationEnabled>true</createDocApplicationEnabled>
<brokerageHelpPhoneNumber>900</brokerageHelpPhoneNumber>
<brokerageReplenishmentSelectionMarkets>true</brokerageReplenishmentSelectionMarkets>
</node>
<node id="194.186.207.23">
<enabled>true</enabled>
<replenishAccountEnabled>true</replenishAccountEnabled>
<replenishAccountInMarginCallEnabled>true</replenishAccountInMarginCallEnabled>
<replenishAccountSearchString>Пополнение Брокерского Счёта</replenishAccountSearchString>
<replenishAccountAgreementFieldCode>field(S133717540667A133717540630)</replenishAccountAgreementFieldCode>
<replenishAccountMarketFieldCode>field(S133717540667A133717540638)</replenishAccountMarketFieldCode>
<createDocApplicationEnabled>true</createDocApplicationEnabled>
<brokerageHelpPhoneNumber>900</brokerageHelpPhoneNumber>
<brokerageReplenishmentSelectionMarkets>true</brokerageReplenishmentSelectionMarkets>
</node>
<node id="mobile.sberbank.ru">
<enabled>true</enabled>
<replenishAccountEnabled>true</replenishAccountEnabled>
<replenishAccountInMarginCallEnabled>true</replenishAccountInMarginCallEnabled>
<replenishAccountSearchString>Пополнение брокерского счета</replenishAccountSearchString>
<replenishAccountAgreementFieldCode>field(S85396525721A85396525552)</replenishAccountAgreementFieldCode>
<replenishAccountMarketFieldCode>field(S85396525721A85396525571)</replenishAccountMarketFieldCode>
<createDocApplicationEnabled>true</createDocApplicationEnabled>
<brokerageHelpPhoneNumber>900</brokerageHelpPhoneNumber>
<brokerageReplenishmentSelectionMarkets>true</brokerageReplenishmentSelectionMarkets>
</node>
<node id="10.21.152.7">
<enabled>true</enabled>
<replenishAccountEnabled>true</replenishAccountEnabled>
<replenishAccountInMarginCallEnabled>true</replenishAccountInMarginCallEnabled>
<replenishAccountSearchString>Пополнение Брокерского Счёта</replenishAccountSearchString>
<replenishAccountAgreementFieldCode>field(S133717540667A133717540630)</replenishAccountAgreementFieldCode>
<replenishAccountMarketFieldCode>field(S133717540667A133717540638)</replenishAccountMarketFieldCode>
<createDocApplicationEnabled>true</createDocApplicationEnabled>
<brokerageHelpPhoneNumber>900</brokerageHelpPhoneNumber>
<brokerageReplenishmentSelectionMarkets>true</brokerageReplenishmentSelectionMarkets>
</node>
</nodes>
<markets>
<market id="0">
<enabled>true</enabled>
</market>
<market id="1">
<enabled>true</enabled>
</market>
<market id="2">
<enabled>false</enabled>
</market>
</markets>
<brokerageEribMarketsMap>
<eribMarket name="Фондовый рынок">
<id>0</id>
</eribMarket>
<eribMarket name="ФБ ММВБ">
<id>0</id>
</eribMarket>
<eribMarket name="ФР ММВБ">
<id>0</id>
</eribMarket>
<eribMarket name="ФР">
<id>0</id>
</eribMarket>
<eribMarket name="Фондовый">
<id>0</id>
</eribMarket>
<eribMarket name="fond">
<id>0</id>
</eribMarket>
<eribMarket name="ФОРТС">
<id>1</id>
</eribMarket>
<eribMarket name="Срочный рынок">
<id>1</id>
</eribMarket>
<eribMarket name="Срочный">
<id>1</id>
</eribMarket>
<eribMarket name="СР">
<id>1</id>
</eribMarket>
<eribMarket name="forts">
<id>1</id>
</eribMarket>
<eribMarket name="Внебиржевой">
<id>2</id>
</eribMarket>
<eribMarket name="Внебиржевой рынок">
<id>2</id>
</eribMarket>
<eribMarket name="ОТС">
<id>2</id>
</eribMarket>
<eribMarket name="Рынок ОТС">
<id>2</id>
</eribMarket>
<eribMarket name="ОТС рынок">
<id>2</id>
</eribMarket>
<eribMarket name="otc">
<id>2</id>
</eribMarket>
<eribMarket name="Валютный рынок">
<id>3</id>
</eribMarket>
<eribMarket name="Валютный">
<id>3</id>
</eribMarket>
<eribMarket name="ВР">
<id>3</id>
</eribMarket>
<eribMarket name="fx">
<id>3</id>
</eribMarket>
</brokerageEribMarketsMap>
</param>
<param name="paymentTransactionsEducationEnabled" description="раздел Образование в платежах">
<type>service</type>
<enabled>true</enabled>
</param>
<param name="brokerage" description="Брокерское обслуживание">
<enabled>true</enabled>
<replenishAccountEnabled>true</replenishAccountEnabled>
<replenishAccountInMarginCallEnabled>true</replenishAccountInMarginCallEnabled>
<nodes>
<node id="ift-node1.testonline.sberbank.ru">
<enabled>true</enabled>
<replenishAccountEnabled>true</replenishAccountEnabled>
<replenishAccountInMarginCallEnabled>true</replenishAccountInMarginCallEnabled>
<replenishAccountSearchString>Пополнение брокерского счета</replenishAccountSearchString>
<replenishAccountAgreementFieldCode>field(S85396525721A85396525552)</replenishAccountAgreementFieldCode>
<replenishAccountMarketFieldCode>field(S85396525721A85396525571)</replenishAccountMarketFieldCode>
<createDocApplicationEnabled>true</createDocApplicationEnabled>
<brokerageHelpPhoneNumber>900</brokerageHelpPhoneNumber>
</node>
<node id="ift-node2.testonline.sberbank.ru">
<enabled>true</enabled>
<replenishAccountEnabled>true</replenishAccountEnabled>
<replenishAccountInMarginCallEnabled>true</replenishAccountInMarginCallEnabled>
<replenishAccountSearchString>Пополнение брокерского счета</replenishAccountSearchString>
<replenishAccountAgreementFieldCode>field(S85396525721A85396525552)</replenishAccountAgreementFieldCode>
<replenishAccountMarketFieldCode>field(S85396525721A85396525571)</replenishAccountMarketFieldCode>
<createDocApplicationEnabled>true</createDocApplicationEnabled>
<brokerageHelpPhoneNumber>900</brokerageHelpPhoneNumber>
</node>
<node id="ift-node1-mp.testonline.sberbank.ru">
<enabled>true</enabled>
<replenishAccountEnabled>true</replenishAccountEnabled>
<replenishAccountInMarginCallEnabled>true</replenishAccountInMarginCallEnabled>
<replenishAccountSearchString>Пополнение брокерского счета</replenishAccountSearchString>
<replenishAccountAgreementFieldCode>field(S85396525721A85396525552)</replenishAccountAgreementFieldCode>
<replenishAccountMarketFieldCode>field(S85396525721A85396525571)</replenishAccountMarketFieldCode>
<createDocApplicationEnabled>true</createDocApplicationEnabled>
<brokerageHelpPhoneNumber>900</brokerageHelpPhoneNumber>
</node>
<node id="ift-node2-mp.testonline.sberbank.ru">
<enabled>true</enabled>
<replenishAccountEnabled>true</replenishAccountEnabled>
<replenishAccountInMarginCallEnabled>true</replenishAccountInMarginCallEnabled>
<replenishAccountSearchString>Пополнение брокерского счета</replenishAccountSearchString>
<replenishAccountAgreementFieldCode>field(S85396525721A85396525552)</replenishAccountAgreementFieldCode>
<replenishAccountMarketFieldCode>field(S85396525721A85396525571)</replenishAccountMarketFieldCode>
<createDocApplicationEnabled>true</createDocApplicationEnabled>
<brokerageHelpPhoneNumber>900</brokerageHelpPhoneNumber>
</node>
<node id="194.186.207.23">
<enabled>true</enabled>
<replenishAccountEnabled>true</replenishAccountEnabled>
<replenishAccountInMarginCallEnabled>true</replenishAccountInMarginCallEnabled>
<replenishAccountSearchString>Пополнение брокерского счета</replenishAccountSearchString>
<replenishAccountAgreementFieldCode>field(S85396525721A85396525552)</replenishAccountAgreementFieldCode>
<replenishAccountMarketFieldCode>field(S85396525721A85396525571)</replenishAccountMarketFieldCode>
<createDocApplicationEnabled>true</createDocApplicationEnabled>
<brokerageHelpPhoneNumber>900</brokerageHelpPhoneNumber>
</node>
<node id="mobile.sberbank.ru">
<enabled>true</enabled>
<replenishAccountEnabled>true</replenishAccountEnabled>
<replenishAccountInMarginCallEnabled>true</replenishAccountInMarginCallEnabled>
<replenishAccountSearchString>Пополнение брокерского счета</replenishAccountSearchString>
<replenishAccountAgreementFieldCode>field(S85396525721A85396525552)</replenishAccountAgreementFieldCode>
<replenishAccountMarketFieldCode>field(S85396525721A85396525571)</replenishAccountMarketFieldCode>
<createDocApplicationEnabled>true</createDocApplicationEnabled>
<brokerageHelpPhoneNumber>900</brokerageHelpPhoneNumber>
</node>
<node id="10.21.152.7">
<enabled>true</enabled>
<replenishAccountEnabled>true</replenishAccountEnabled>
<replenishAccountInMarginCallEnabled>true</replenishAccountInMarginCallEnabled>
<replenishAccountSearchString>Пополнение брокерского счета</replenishAccountSearchString>
<replenishAccountAgreementFieldCode>field(S85396525721A85396525552)</replenishAccountAgreementFieldCode>
<replenishAccountMarketFieldCode>field(S85396525721A85396525571)</replenishAccountMarketFieldCode>
<createDocApplicationEnabled>true</createDocApplicationEnabled>
<brokerageHelpPhoneNumber>900</brokerageHelpPhoneNumber>
</node>
</nodes>
<markets>
<market id="0">
<enabled>true</enabled>
</market>
<market id="1">
<enabled>true</enabled>
</market>
<market id="2">
<enabled>false</enabled>
</market>
</markets>
</param>
<param name="paymentTransactionsEducationEnabled" description="раздел Образование в платежах">
<type>service</type>
<enabled>true</enabled>
</param>
<param name="TxPushSuggestion" description="">
<type>setting</type>
<enabled>true</enabled>
<periodInDays>1</periodInDays>
<number>5</number>
</param>
<param name="nodeDoNotShowPushTutorialForApiLevels" description="">
<type>list</type>
<nodes>
<node id="greenfield1.online.sberbank.ru">
<enabled>true</enabled>
</node>
<node id="greenfield2.online.sberbank.ru">
<enabled>true</enabled>
</node>
<node id="mobile.sberbank.ru">
<enabled>true</enabled>
</node>
<node id="ift-node1.testonline.sberbank.ru">
<enabled>true</enabled>
</node>
<node id="ift-node2.testonline.sberbank.ru">
<enabled>true</enabled>
</node>
<node id="ift-node1-mp.testonline.sberbank.ru">
<enabled>true</enabled>
</node>
<node id="ift-node2-mp.testonline.sberbank.ru">
<enabled>true</enabled>
</node>
</nodes>
</param>
<param name="CardPushEnabled" description="">
<type>setting</type>
<enabled>true</enabled>
</param>
<param name="DDAPermissions" description="Консолидированные включатели функционала Data Driven App">
<type>list</type>
<enabled>true</enabled>
<nodes>
<node id="node0.online.sberbank.ru">
<SmartSearch>true</SmartSearch>
<NBAA>true</NBAA>
<SearchHistory>true</SearchHistory>
<DepthNBAA>60</DepthNBAA>
<MonthAmountNBAA>3</MonthAmountNBAA>
<SearchForHistoryWithListDo>true</SearchForHistoryWithListDo>
<HistoryPageCount>3</HistoryPageCount>
<RequestDelay>400</RequestDelay>
<NBAAForHistoryDisabled>true</NBAAForHistoryDisabled>
<NBAAForPaymentsDisabled>true</NBAAForPaymentsDisabled>
<MainNotification>true</MainNotification>
<DDPSmartNbaaEnabled>true</DDPSmartNbaaEnabled>
<DDPContactsWeightsEnabled>true</DDPContactsWeightsEnabled>
<DDPNBAARepeatEnabled>true</DDPNBAARepeatEnabled>
<NLPEnabled>true</NLPEnabled>
<ApplePayAdd>false</ApplePayAdd>
<BlockCardAdd>true</BlockCardAdd>
<CurrencyCardBankDetail>true</CurrencyCardBankDetail>
</node>
<node id="node1.online.sberbank.ru">
<SmartSearch>true</SmartSearch>
<NBAA>true</NBAA>
<SearchHistory>true</SearchHistory>
<DepthNBAA>60</DepthNBAA>
<MonthAmountNBAA>3</MonthAmountNBAA>
<SearchForHistoryWithListDo>true</SearchForHistoryWithListDo>
<HistoryPageCount>3</HistoryPageCount>
<RequestDelay>400</RequestDelay>
<NBAAForHistoryDisabled>true</NBAAForHistoryDisabled>
<NBAAForPaymentsDisabled>true</NBAAForPaymentsDisabled>
<MainNotification>true</MainNotification>
<DDPSmartNbaaEnabled>true</DDPSmartNbaaEnabled>
<DDPContactsWeightsEnabled>true</DDPContactsWeightsEnabled>
<DDPNBAARepeatEnabled>true</DDPNBAARepeatEnabled>
<NLPEnabled>true</NLPEnabled>
<ApplePayAdd>false</ApplePayAdd>
<BlockCardAdd>true</BlockCardAdd>
<CurrencyCardBankDetail>true</CurrencyCardBankDetail>
</node>
<node id="node2.online.sberbank.ru">
<SmartSearch>true</SmartSearch>
<NBAA>true</NBAA>
<SearchHistory>true</SearchHistory>
<DepthNBAA>60</DepthNBAA>
<MonthAmountNBAA>3</MonthAmountNBAA>
<SearchForHistoryWithListDo>true</SearchForHistoryWithListDo>
<HistoryPageCount>3</HistoryPageCount>
<RequestDelay>400</RequestDelay>
<NBAAForHistoryDisabled>true</NBAAForHistoryDisabled>
<NBAAForPaymentsDisabled>true</NBAAForPaymentsDisabled>
<MainNotification>true</MainNotification>
<DDPSmartNbaaEnabled>true</DDPSmartNbaaEnabled>
<DDPContactsWeightsEnabled>true</DDPContactsWeightsEnabled>
<DDPNBAARepeatEnabled>true</DDPNBAARepeatEnabled>
<NLPEnabled>true</NLPEnabled>
<ApplePayAdd>false</ApplePayAdd>
<BlockCardAdd>true</BlockCardAdd>
<CurrencyCardBankDetail>true</CurrencyCardBankDetail>
</node>
<node id="node3.online.sberbank.ru">
<SmartSearch>true</SmartSearch>
<NBAA>true</NBAA>
<SearchHistory>true</SearchHistory>
<DepthNBAA>60</DepthNBAA>
<MonthAmountNBAA>3</MonthAmountNBAA>
<SearchForHistoryWithListDo>true</SearchForHistoryWithListDo>
<HistoryPageCount>3</HistoryPageCount>
<RequestDelay>400</RequestDelay>
<NBAAForHistoryDisabled>true</NBAAForHistoryDisabled>
<NBAAForPaymentsDisabled>true</NBAAForPaymentsDisabled>
<MainNotification>true</MainNotification>
<DDPSmartNbaaEnabled>true</DDPSmartNbaaEnabled>
<DDPContactsWeightsEnabled>true</DDPContactsWeightsEnabled>
<DDPNBAARepeatEnabled>true</DDPNBAARepeatEnabled>
<NLPEnabled>true</NLPEnabled>
<ApplePayAdd>false</ApplePayAdd>
<BlockCardAdd>true</BlockCardAdd>
<CurrencyCardBankDetail>true</CurrencyCardBankDetail>
</node>
<node id="greenfield1.online.sberbank.ru">
<SmartSearch>true</SmartSearch>
<NBAA>true</NBAA>
<SearchHistory>true</SearchHistory>
<DepthNBAA>60</DepthNBAA>
<MonthAmountNBAA>3</MonthAmountNBAA>
<SearchForHistoryWithListDo>true</SearchForHistoryWithListDo>
<HistoryPageCount>3</HistoryPageCount>
<RequestDelay>400</RequestDelay>
<NBAAForHistoryDisabled>true</NBAAForHistoryDisabled>
<NBAAForPaymentsDisabled>true</NBAAForPaymentsDisabled>
<MainNotification>true</MainNotification>
<DDPSmartNbaaEnabled>true</DDPSmartNbaaEnabled>
<DDPContactsWeightsEnabled>true</DDPContactsWeightsEnabled>
<DDPNBAARepeatEnabled>true</DDPNBAARepeatEnabled>
<DDPBusinessChatsEnabled>true</DDPBusinessChatsEnabled>
<NLPEnabled>true</NLPEnabled>
<ApplePayAdd>false</ApplePayAdd>
<BlockCardAdd>true</BlockCardAdd>
<CurrencyCardBankDetail>true</CurrencyCardBankDetail>
</node>
<node id="greenfield2.online.sberbank.ru">
<SmartSearch>true</SmartSearch>
<NBAA>true</NBAA>
<SearchHistory>true</SearchHistory>
<DepthNBAA>60</DepthNBAA>
<MonthAmountNBAA>3</MonthAmountNBAA>
<SearchForHistoryWithListDo>true</SearchForHistoryWithListDo>
<HistoryPageCount>3</HistoryPageCount>
<RequestDelay>400</RequestDelay>
<NBAAForHistoryDisabled>true</NBAAForHistoryDisabled>
<NBAAForPaymentsDisabled>true</NBAAForPaymentsDisabled>
<MainNotification>true</MainNotification>
<DDPSmartNbaaEnabled>true</DDPSmartNbaaEnabled>
<DDPContactsWeightsEnabled>true</DDPContactsWeightsEnabled>
<DDPNBAARepeatEnabled>true</DDPNBAARepeatEnabled>
<NLPEnabled>true</NLPEnabled>
<ApplePayAdd>false</ApplePayAdd>
<BlockCardAdd>true</BlockCardAdd>
<CurrencyCardBankDetail>true</CurrencyCardBankDetail>
</node>
<node id="194.186.207.23">
<SmartSearch>true</SmartSearch>
<NBAA>true</NBAA>
<SearchHistory>true</SearchHistory>
<DepthNBAA>60</DepthNBAA>
<MonthAmountNBAA>3</MonthAmountNBAA>
<SearchForHistoryWithListDo>true</SearchForHistoryWithListDo>
<HistoryPageCount>3</HistoryPageCount>
<RequestDelay>400</RequestDelay>
<NBAAForHistoryDisabled>true</NBAAForHistoryDisabled>
<NBAAForPaymentsDisabled>true</NBAAForPaymentsDisabled>
<MainNotification>true</MainNotification>
<DDPSmartNbaaEnabled>true</DDPSmartNbaaEnabled>
<DDPContactsWeightsEnabled>true</DDPContactsWeightsEnabled>
<DDPNBAARepeatEnabled>true</DDPNBAARepeatEnabled>
<NLPEnabled>true</NLPEnabled>
<ApplePayAdd>false</ApplePayAdd>
<BlockCardAdd>true</BlockCardAdd>
<CurrencyCardBankDetail>true</CurrencyCardBankDetail>
</node>
<node id="mobile.sberbank.ru">
<SmartSearch>true</SmartSearch>
<NBAA>true</NBAA>
<SearchHistory>true</SearchHistory>
<DepthNBAA>60</DepthNBAA>
<MonthAmountNBAA>3</MonthAmountNBAA>
<SearchForHistoryWithListDo>true</SearchForHistoryWithListDo>
<HistoryPageCount>3</HistoryPageCount>
<RequestDelay>400</RequestDelay>
<NBAAForHistoryDisabled>true</NBAAForHistoryDisabled>
<NBAAForPaymentsDisabled>true</NBAAForPaymentsDisabled>
<MainNotification>true</MainNotification>
<DDPSmartNbaaEnabled>true</DDPSmartNbaaEnabled>
<DDPContactsWeightsEnabled>true</DDPContactsWeightsEnabled>
<DDPNBAARepeatEnabled>true</DDPNBAARepeatEnabled>
<NLPEnabled>true</NLPEnabled>
<ApplePayAdd>false</ApplePayAdd>
<BlockCardAdd>true</BlockCardAdd>
<CurrencyCardBankDetail>true</CurrencyCardBankDetail>
</node>
<node id="ift-node1.testonline.sberbank.ru">
<SmartSearch>true</SmartSearch>
<NBAA>true</NBAA>
<SearchHistory>true</SearchHistory>
<DepthNBAA>60</DepthNBAA>
<MonthAmountNBAA>3</MonthAmountNBAA>
<SearchForHistoryWithListDo>true</SearchForHistoryWithListDo>
<HistoryPageCount>3</HistoryPageCount>
<RequestDelay>400</RequestDelay>
<NBAAForHistoryDisabled>true</NBAAForHistoryDisabled>
<NBAAForPaymentsDisabled>true</NBAAForPaymentsDisabled>
<MainNotification>true</MainNotification>
<DDPSmartNbaaEnabled>true</DDPSmartNbaaEnabled>
<DDPContactsWeightsEnabled>true</DDPContactsWeightsEnabled>
<DDPNBAARepeatEnabled>true</DDPNBAARepeatEnabled>
<NLPEnabled>true</NLPEnabled>
<ApplePayAdd>false</ApplePayAdd>
<BlockCardAdd>true</BlockCardAdd>
<CurrencyCardBankDetail>true</CurrencyCardBankDetail>
</node>
<node id="ift-node2.testonline.sberbank.ru">
<SmartSearch>true</SmartSearch>
<NBAA>true</NBAA>
<SearchHistory>true</SearchHistory>
<DepthNBAA>60</DepthNBAA>
<MonthAmountNBAA>3</MonthAmountNBAA>
<SearchForHistoryWithListDo>true</SearchForHistoryWithListDo>
<HistoryPageCount>3</HistoryPageCount>
<RequestDelay>400</RequestDelay>
<NBAAForHistoryDisabled>true</NBAAForHistoryDisabled>
<NBAAForPaymentsDisabled>true</NBAAForPaymentsDisabled>
<MainNotification>true</MainNotification>
<DDPSmartNbaaEnabled>true</DDPSmartNbaaEnabled>
<DDPContactsWeightsEnabled>true</DDPContactsWeightsEnabled>
<DDPNBAARepeatEnabled>true</DDPNBAARepeatEnabled>
<NLPEnabled>true</NLPEnabled>
<ApplePayAdd>false</ApplePayAdd>
<BlockCardAdd>true</BlockCardAdd>
<CurrencyCardBankDetail>true</CurrencyCardBankDetail>
</node>
<node id="ift-node1-mp.testonline.sberbank.ru">
<SmartSearch>true</SmartSearch>
<NBAA>true</NBAA>
<SearchHistory>true</SearchHistory>
<DepthNBAA>60</DepthNBAA>
<MonthAmountNBAA>3</MonthAmountNBAA>
<SearchForHistoryWithListDo>true</SearchForHistoryWithListDo>
<HistoryPageCount>3</HistoryPageCount>
<RequestDelay>400</RequestDelay>
<NBAAForHistoryDisabled>true</NBAAForHistoryDisabled>
<NBAAForPaymentsDisabled>true</NBAAForPaymentsDisabled>
<MainNotification>true</MainNotification>
<DDPSmartNbaaEnabled>true</DDPSmartNbaaEnabled>
<DDPContactsWeightsEnabled>true</DDPContactsWeightsEnabled>
<DDPNBAARepeatEnabled>true</DDPNBAARepeatEnabled>
<NLPEnabled>true</NLPEnabled>
<ApplePayAdd>false</ApplePayAdd>
<BlockCardAdd>true</BlockCardAdd>
<CurrencyCardBankDetail>true</CurrencyCardBankDetail>
</node>
<node id="ift-node2-mp.testonline.sberbank.ru">
<SmartSearch>true</SmartSearch>
<NBAA>true</NBAA>
<SearchHistory>true</SearchHistory>
<DepthNBAA>60</DepthNBAA>
<MonthAmountNBAA>3</MonthAmountNBAA>
<SearchForHistoryWithListDo>true</SearchForHistoryWithListDo>
<HistoryPageCount>3</HistoryPageCount>
<RequestDelay>400</RequestDelay>
<NBAAForHistoryDisabled>true</NBAAForHistoryDisabled>
<NBAAForPaymentsDisabled>true</NBAAForPaymentsDisabled>
<MainNotification>true</MainNotification>
<DDPSmartNbaaEnabled>true</DDPSmartNbaaEnabled>
<DDPContactsWeightsEnabled>true</DDPContactsWeightsEnabled>
<DDPNBAARepeatEnabled>true</DDPNBAARepeatEnabled>
<NLPEnabled>true</NLPEnabled>
<ApplePayAdd>false</ApplePayAdd>
<BlockCardAdd>true</BlockCardAdd>
<CurrencyCardBankDetail>true</CurrencyCardBankDetail>
</node>
<node id="msv-node2.testonline.sberbank.ru">
<SmartSearch>true</SmartSearch>
<NBAA>true</NBAA>
<SearchHistory>true</SearchHistory>
</node>
<node id="ift-node5.testonline.sberbank.ru">
<SmartSearch>true</SmartSearch>
<NBAA>true</NBAA>
<SearchHistory>true</SearchHistory>
</node>
<node id="ift-node5-mp.testonline.sberbank.ru">
<SmartSearch>true</SmartSearch>
<NBAA>true</NBAA>
<SearchHistory>true</SearchHistory>
</node>
</nodes>
</param>
<param name="InsuranceProducts" description="Продажа страховых продуктов">
<type>list</type>
<nodes>
<node id="greenfield1.online.sberbank.ru">
<InsuranceProductsEnabled>true</InsuranceProductsEnabled>
</node>
<node id="greenfield2.online.sberbank.ru">
<InsuranceProductsEnabled>true</InsuranceProductsEnabled>
</node>
<node id="194.186.207.23">
<InsuranceProductsEnabled>true</InsuranceProductsEnabled>
</node>
<node id="mobile.sberbank.ru">
<InsuranceProductsEnabled>true</InsuranceProductsEnabled>
</node>
<node id="node0.online.sberbank.ru">
<InsuranceProductsEnabled>true</InsuranceProductsEnabled>
</node>
<node id="node1.online.sberbank.ru">
<InsuranceProductsEnabled>true</InsuranceProductsEnabled>
</node>
<node id="node2.online.sberbank.ru">
<InsuranceProductsEnabled>true</InsuranceProductsEnabled>
</node>
<node id="node3.online.sberbank.ru">
<InsuranceProductsEnabled>true</InsuranceProductsEnabled>
</node>
<node id="ift-node1.testonline.sberbank.ru">
<InsuranceProductsEnabled>true</InsuranceProductsEnabled>
</node>
<node id="ift-node2.testonline.sberbank.ru">
<InsuranceProductsEnabled>true</InsuranceProductsEnabled>
</node>
<node id="ift-node1-mp.testonline.sberbank.ru">
<InsuranceProductsEnabled>true</InsuranceProductsEnabled>
</node>
<node id="ift-node2-mp.testonline.sberbank.ru">
<InsuranceProductsEnabled>true</InsuranceProductsEnabled>
</node>
<node id="10.21.152.7">
<InsuranceProductsEnabled>true</InsuranceProductsEnabled>
</node>
<node id="msv-node2.testonline.sberbank.ru">
<InsuranceProductsEnabled>true</InsuranceProductsEnabled>
</node>
</nodes>
</param>
<param name="providerUFSPaymentsEnabled" description="Платежи в МП на ЕФС">
<type>setting</type>
<enabled>true</enabled>
</param>
<param name="PersonalDataProfile" description="Редактирование/добавление персональных данных клиента">
<type>list</type>
<enabled>true</enabled>
<nodes>
<node id="mobile.sberbank.ru">
<enabled>true</enabled>
<PassportProfile>false</PassportProfile>
<EmailProfile>true</EmailProfile>
<PhoneNumberProfile>true</PhoneNumberProfile>
<DriversLicenseProfile>true</DriversLicenseProfile>
<STSProfile>true</STSProfile>
<InnProfile>true</InnProfile>
<SnilsProfile>true</SnilsProfile>
<HistoryOperationProfile>true</HistoryOperationProfile>
<EmailEditProfile>true</EmailEditProfile>
<PhoneNumberEditProfile>true</PhoneNumberEditProfile>
<SnilsEditProfile>false</SnilsEditProfile>
<InnEditProfile>false</InnEditProfile>
<PhoneNumberSMSConfirmationProfile>true</PhoneNumberSMSConfirmationProfile>
<EmailDoubleAddProfile>true</EmailDoubleAddProfile>
<PhoneNumberDoubleAddProfile>true</PhoneNumberDoubleAddProfile>
</node>
<node id="psinode2.testonline.sberbank.ru">
<enabled>true</enabled>
<PassportProfile>false</PassportProfile>
<EmailProfile>true</EmailProfile>
<PhoneNumberProfile>true</PhoneNumberProfile>
<DriversLicenseProfile>true</DriversLicenseProfile>
<STSProfile>true</STSProfile>
<InnProfile>true</InnProfile>
<SnilsProfile>true</SnilsProfile>
<HistoryOperationProfile>true</HistoryOperationProfile>
<EmailEditProfile>true</EmailEditProfile>
<PhoneNumberEditProfile>true</PhoneNumberEditProfile>
<SnilsEditProfile>false</SnilsEditProfile>
<InnEditProfile>false</InnEditProfile>
<PhoneNumberSMSConfirmationProfile>true</PhoneNumberSMSConfirmationProfile>
<EmailDoubleAddProfile>true</EmailDoubleAddProfile>
<PhoneNumberDoubleAddProfile>true</PhoneNumberDoubleAddProfile>
</node>
<node id="psinode1.testonline.sberbank.ru">
<enabled>true</enabled>
<PassportProfile>false</PassportProfile>
<EmailProfile>true</EmailProfile>
<PhoneNumberProfile>true</PhoneNumberProfile>
<DriversLicenseProfile>true</DriversLicenseProfile>
<STSProfile>true</STSProfile>
<InnProfile>true</InnProfile>
<SnilsProfile>true</SnilsProfile>
<HistoryOperationProfile>true</HistoryOperationProfile>
<EmailEditProfile>true</EmailEditProfile>
<PhoneNumberEditProfile>true</PhoneNumberEditProfile>
<SnilsEditProfile>false</SnilsEditProfile>
<InnEditProfile>false</InnEditProfile>
<PhoneNumberSMSConfirmationProfile>true</PhoneNumberSMSConfirmationProfile>
<EmailDoubleAddProfile>true</EmailDoubleAddProfile>
<PhoneNumberDoubleAddProfile>true</PhoneNumberDoubleAddProfile>
</node>
<node id="194.186.207.23">
<enabled>true</enabled>
<PassportProfile>false</PassportProfile>
<EmailProfile>true</EmailProfile>
<PhoneNumberProfile>true</PhoneNumberProfile>
<DriversLicenseProfile>true</DriversLicenseProfile>
<STSProfile>true</STSProfile>
<InnProfile>true</InnProfile>
<SnilsProfile>true</SnilsProfile>
<HistoryOperationProfile>true</HistoryOperationProfile>
<EmailEditProfile>true</EmailEditProfile>
<PhoneNumberEditProfile>true</PhoneNumberEditProfile>
<SnilsEditProfile>false</SnilsEditProfile>
<InnEditProfile>false</InnEditProfile>
<PhoneNumberSMSConfirmationProfile>true</PhoneNumberSMSConfirmationProfile>
<EmailDoubleAddProfile>true</EmailDoubleAddProfile>
<PhoneNumberDoubleAddProfile>true</PhoneNumberDoubleAddProfile>
</node>
<node id="ift-node5-mp.testonline.sberbank.ru">
<enabled>true</enabled>
<PassportProfile>true</PassportProfile>
<EmailProfile>true</EmailProfile>
<PhoneNumberProfile>true</PhoneNumberProfile>
<DriversLicenseProfile>true</DriversLicenseProfile>
<STSProfile>true</STSProfile>
<InnProfile>true</InnProfile>
<SnilsProfile>true</SnilsProfile>
<HistoryOperationProfile>true</HistoryOperationProfile>
<EmailEditProfile>true</EmailEditProfile>
<PhoneNumberEditProfile>true</PhoneNumberEditProfile>
<SnilsEditProfile>false</SnilsEditProfile>
<InnEditProfile>false</InnEditProfile>
<PhoneNumberSMSConfirmationProfile>true</PhoneNumberSMSConfirmationProfile>
<CashingPersonalDataProfile>false</CashingPersonalDataProfile>
<EmailDoubleAddProfile>true</EmailDoubleAddProfile>
<PhoneNumberDoubleAddProfile>true</PhoneNumberDoubleAddProfile>
</node>
<node id="ift-node1.testonline.sberbank.ru">
<enabled>true</enabled>
<PassportProfile>false</PassportProfile>
<EmailProfile>true</EmailProfile>
<PhoneNumberProfile>true</PhoneNumberProfile>
<DriversLicenseProfile>true</DriversLicenseProfile>
<STSProfile>true</STSProfile>
<InnProfile>true</InnProfile>
<SnilsProfile>true</SnilsProfile>
<HistoryOperationProfile>true</HistoryOperationProfile>
<EmailEditProfile>true</EmailEditProfile>
<PhoneNumberEditProfile>true</PhoneNumberEditProfile>
<SnilsEditProfile>false</SnilsEditProfile>
<InnEditProfile>false</InnEditProfile>
<PhoneNumberSMSConfirmationProfile>true</PhoneNumberSMSConfirmationProfile>
<EmailDoubleAddProfile>true</EmailDoubleAddProfile>
<PhoneNumberDoubleAddProfile>true</PhoneNumberDoubleAddProfile>
</node>
<node id="ift-node2.testonline.sberbank.ru">
<enabled>true</enabled>
<PassportProfile>false</PassportProfile>
<EmailProfile>true</EmailProfile>
<PhoneNumberProfile>true</PhoneNumberProfile>
<DriversLicenseProfile>true</DriversLicenseProfile>
<STSProfile>true</STSProfile>
<InnProfile>true</InnProfile>
<SnilsProfile>true</SnilsProfile>
<HistoryOperationProfile>true</HistoryOperationProfile>
<EmailEditProfile>true</EmailEditProfile>
<PhoneNumberEditProfile>true</PhoneNumberEditProfile>
<SnilsEditProfile>false</SnilsEditProfile>
<InnEditProfile>false</InnEditProfile>
<PhoneNumberSMSConfirmationProfile>true</PhoneNumberSMSConfirmationProfile>
<EmailDoubleAddProfile>true</EmailDoubleAddProfile>
<PhoneNumberDoubleAddProfile>true</PhoneNumberDoubleAddProfile>
</node>
<node id="ift-node1-mp.testonline.sberbank.ru">
<enabled>true</enabled>
<PassportProfile>false</PassportProfile>
<EmailProfile>true</EmailProfile>
<PhoneNumberProfile>true</PhoneNumberProfile>
<DriversLicenseProfile>true</DriversLicenseProfile>
<STSProfile>true</STSProfile>
<InnProfile>true</InnProfile>
<SnilsProfile>true</SnilsProfile>
<HistoryOperationProfile>true</HistoryOperationProfile>
<EmailEditProfile>true</EmailEditProfile>
<PhoneNumberEditProfile>true</PhoneNumberEditProfile>
<SnilsEditProfile>false</SnilsEditProfile>
<InnEditProfile>false</InnEditProfile>
<PhoneNumberSMSConfirmationProfile>true</PhoneNumberSMSConfirmationProfile>
<EmailDoubleAddProfile>true</EmailDoubleAddProfile>
<PhoneNumberDoubleAddProfile>true</PhoneNumberDoubleAddProfile>
</node>
<node id="ift-node2-mp.testonline.sberbank.ru">
<enabled>true</enabled>
<PassportProfile>false</PassportProfile>
<EmailProfile>true</EmailProfile>
<PhoneNumberProfile>true</PhoneNumberProfile>
<DriversLicenseProfile>true</DriversLicenseProfile>
<STSProfile>true</STSProfile>
<InnProfile>true</InnProfile>
<SnilsProfile>true</SnilsProfile>
<HistoryOperationProfile>true</HistoryOperationProfile>
<EmailEditProfile>true</EmailEditProfile>
<PhoneNumberEditProfile>true</PhoneNumberEditProfile>
<SnilsEditProfile>false</SnilsEditProfile>
<InnEditProfile>false</InnEditProfile>
<PhoneNumberSMSConfirmationProfile>true</PhoneNumberSMSConfirmationProfile>
<EmailDoubleAddProfile>true</EmailDoubleAddProfile>
<PhoneNumberDoubleAddProfile>true</PhoneNumberDoubleAddProfile>
</node>
</nodes>
</param>
<param name="SberbankIDMerchantIcon" description="Иконка потребителя">
<type>source</type>
<link>/SBERBANKID/icons/client_id.png</link>
</param>
<param name="HistoryOperation" description="Вкладка История. Блоки работают по логическому ИЛИ">
<type>list</type>
<enabled>true</enabled>
<Global/>
<nodes>
<node id="node0.online.sberbank.ru">
<externalOperationForm>true</externalOperationForm>
<newOperationsHistoryList>true</newOperationsHistoryList>
<hideDaySum>false</hideDaySum>
<tagAll>true</tagAll>
<additionalOperationForm>true</additionalOperationForm>
<logotypes>true</logotypes>
<routerForUFS>true</routerForUFS>
<replaceInvoicesToHistory>true</replaceInvoicesToHistory>
<smartSearchFromHistory>true</smartSearchFromHistory>
<receiveOperationsByTag>true</receiveOperationsByTag>
<replaceInvoicesToHistoryOnAccount>true</replaceInvoicesToHistoryOnAccount>
<refactoredOperationDetails>true</refactoredOperationDetails>
<referenceOnOperation>true</referenceOnOperation>
<logotypesInOperationDetails>true</logotypesInOperationDetails>
<mapInOperationDetails>true</mapInOperationDetails>
</node>
<node id="node1.online.sberbank.ru">
<externalOperationForm>true</externalOperationForm>
<newOperationsHistoryList>true</newOperationsHistoryList>
<hideDaySum>false</hideDaySum>
<tagAll>true</tagAll>
<additionalOperationForm>true</additionalOperationForm>
<logotypes>true</logotypes>
<routerForUFS>true</routerForUFS>
<replaceInvoicesToHistory>true</replaceInvoicesToHistory>
<smartSearchFromHistory>true</smartSearchFromHistory>
<receiveOperationsByTag>true</receiveOperationsByTag>
<replaceInvoicesToHistoryOnAccount>true</replaceInvoicesToHistoryOnAccount>
<refactoredOperationDetails>true</refactoredOperationDetails>
<referenceOnOperation>true</referenceOnOperation>
<logotypesInOperationDetails>true</logotypesInOperationDetails>
<mapInOperationDetails>true</mapInOperationDetails>
</node>
<node id="node2.online.sberbank.ru">
<externalOperationForm>true</externalOperationForm>
<newOperationsHistoryList>true</newOperationsHistoryList>
<hideDaySum>false</hideDaySum>
<tagAll>true</tagAll>
<additionalOperationForm>true</additionalOperationForm>
<logotypes>true</logotypes>
<routerForUFS>true</routerForUFS>
<replaceInvoicesToHistory>true</replaceInvoicesToHistory>
<smartSearchFromHistory>true</smartSearchFromHistory>
<receiveOperationsByTag>true</receiveOperationsByTag>
<replaceInvoicesToHistoryOnAccount>true</replaceInvoicesToHistoryOnAccount>
<refactoredOperationDetails>true</refactoredOperationDetails>
<referenceOnOperation>true</referenceOnOperation>
<logotypesInOperationDetails>true</logotypesInOperationDetails>
<mapInOperationDetails>true</mapInOperationDetails>
</node>
<node id="node3.online.sberbank.ru">
<externalOperationForm>true</externalOperationForm>
<newOperationsHistoryList>true</newOperationsHistoryList>
<hideDaySum>false</hideDaySum>
<tagAll>true</tagAll>
<additionalOperationForm>true</additionalOperationForm>
<logotypes>true</logotypes>
<routerForUFS>true</routerForUFS>
<replaceInvoicesToHistory>true</replaceInvoicesToHistory>
<smartSearchFromHistory>true</smartSearchFromHistory>
<receiveOperationsByTag>true</receiveOperationsByTag>
<replaceInvoicesToHistoryOnAccount>true</replaceInvoicesToHistoryOnAccount>
<refactoredOperationDetails>true</refactoredOperationDetails>
<referenceOnOperation>true</referenceOnOperation>
<logotypesInOperationDetails>true</logotypesInOperationDetails>
<mapInOperationDetails>true</mapInOperationDetails>
</node>
<node id="greenfield1.online.sberbank.ru">
<externalOperationForm>true</externalOperationForm>
<newOperationsHistoryList>true</newOperationsHistoryList>
<hideDaySum>false</hideDaySum>
<tagAll>true</tagAll>
<additionalOperationForm>true</additionalOperationForm>
<logotypes>true</logotypes>
<routerForUFS>true</routerForUFS>
<replaceInvoicesToHistory>true</replaceInvoicesToHistory>
<smartSearchFromHistory>false</smartSearchFromHistory>
<receiveOperationsByTag>true</receiveOperationsByTag>
<replaceInvoicesToHistoryOnAccount>true</replaceInvoicesToHistoryOnAccount>
<refactoredOperationDetails>true</refactoredOperationDetails>
<referenceOnOperation>true</referenceOnOperation>
<logotypesInOperationDetails>true</logotypesInOperationDetails>
<mapInOperationDetails>true</mapInOperationDetails>
<advertisementInHistoryList>true</advertisementInHistoryList>
</node>
<node id="greenfield2.online.sberbank.ru">
<externalOperationForm>true</externalOperationForm>
<newOperationsHistoryList>true</newOperationsHistoryList>
<hideDaySum>false</hideDaySum>
<tagAll>true</tagAll>
<additionalOperationForm>true</additionalOperationForm>
<logotypes>true</logotypes>
<routerForUFS>true</routerForUFS>
<replaceInvoicesToHistory>true</replaceInvoicesToHistory>
<smartSearchFromHistory>true</smartSearchFromHistory>
<receiveOperationsByTag>true</receiveOperationsByTag>
<replaceInvoicesToHistoryOnAccount>true</replaceInvoicesToHistoryOnAccount>
<refactoredOperationDetails>true</refactoredOperationDetails>
<referenceOnOperation>true</referenceOnOperation>
<logotypesInOperationDetails>true</logotypesInOperationDetails>
<mapInOperationDetails>true</mapInOperationDetails>
</node>
<node id="mobile.sberbank.ru">
<externalOperationForm>true</externalOperationForm>
<newOperationsHistoryList>true</newOperationsHistoryList>
<hideDaySum>false</hideDaySum>
<tagAll>true</tagAll>
<additionalOperationForm>true</additionalOperationForm>
<logotypes>true</logotypes>
<routerForUFS>true</routerForUFS>
<replaceInvoicesToHistory>true</replaceInvoicesToHistory>
<smartSearchFromHistory>true</smartSearchFromHistory>
<receiveOperationsByTag>true</receiveOperationsByTag>
<replaceInvoicesToHistoryOnAccount>true</replaceInvoicesToHistoryOnAccount>
<refactoredOperationDetails>true</refactoredOperationDetails>
<referenceOnOperation>true</referenceOnOperation>
<logotypesInOperationDetails>true</logotypesInOperationDetails>
<mapInOperationDetails>true</mapInOperationDetails>
<arrestAndPunishmentOperations>true</arrestAndPunishmentOperations>
<advertisementInHistoryList>true</advertisementInHistoryList>
<extEpsPaymentOperation>true</extEpsPaymentOperation>
</node>
<node id="ift-node1.testonline.sberbank.ru">
<externalOperationForm>true</externalOperationForm>
<newOperationsHistoryList>true</newOperationsHistoryList>
<hideDaySum>false</hideDaySum>
<tagAll>true</tagAll>
<additionalOperationForm>true</additionalOperationForm>
<logotypes>true</logotypes>
<routerForUFS>true</routerForUFS>
<receiveOperationsByTag>true</receiveOperationsByTag>
<replaceInvoicesToHistoryOnAccount>true</replaceInvoicesToHistoryOnAccount>
<refactoredOperationDetails>true</refactoredOperationDetails>
<smartSearchFromHistory>true</smartSearchFromHistory>
<referenceOnOperation>true</referenceOnOperation>
<logotypesInOperationDetails>true</logotypesInOperationDetails>
<arrestAndPunishmentOperations>true</arrestAndPunishmentOperations>
<mapInOperationDetails>true</mapInOperationDetails>
<advertisementInHistoryList>true</advertisementInHistoryList>
<extEpsPaymentOperation>true</extEpsPaymentOperation>
</node>
<node id="ift-node2.testonline.sberbank.ru">
<externalOperationForm>true</externalOperationForm>
<newOperationsHistoryList>true</newOperationsHistoryList>
<hideDaySum>false</hideDaySum>
<tagAll>true</tagAll>
<additionalOperationForm>true</additionalOperationForm>
<logotypes>true</logotypes>
<routerForUFS>true</routerForUFS>
<replaceInvoicesToHistory>true</replaceInvoicesToHistory>
<receiveOperationsByTag>true</receiveOperationsByTag>
<replaceInvoicesToHistoryOnAccount>true</replaceInvoicesToHistoryOnAccount>
<refactoredOperationDetails>true</refactoredOperationDetails>
<smartSearchFromHistory>true</smartSearchFromHistory>
<referenceOnOperation>true</referenceOnOperation>
<logotypesInOperationDetails>true</logotypesInOperationDetails>
<arrestAndPunishmentOperations>true</arrestAndPunishmentOperations>
<mapInOperationDetails>true</mapInOperationDetails>
<advertisementInHistoryList>true</advertisementInHistoryList>
<extEpsPaymentOperation>true</extEpsPaymentOperation>
</node>
<node id="ift-node1-mp.testonline.sberbank.ru">
<externalOperationForm>true</externalOperationForm>
<newOperationsHistoryList>true</newOperationsHistoryList>
<hideDaySum>false</hideDaySum>
<tagAll>true</tagAll>
<additionalOperationForm>true</additionalOperationForm>
<logotypes>true</logotypes>
<routerForUFS>true</routerForUFS>
<replaceInvoicesToHistory>true</replaceInvoicesToHistory>
<receiveOperationsByTag>true</receiveOperationsByTag>
<replaceInvoicesToHistoryOnAccount>true</replaceInvoicesToHistoryOnAccount>
<refactoredOperationDetails>true</refactoredOperationDetails>
<smartSearchFromHistory>true</smartSearchFromHistory>
<referenceOnOperation>true</referenceOnOperation>
<logotypesInOperationDetails>true</logotypesInOperationDetails>
<arrestAndPunishmentOperations>true</arrestAndPunishmentOperations>
<mapInOperationDetails>true</mapInOperationDetails>
<advertisementInHistoryList>true</advertisementInHistoryList>
<extEpsPaymentOperation>true</extEpsPaymentOperation>
</node>
<node id="ift-node2-mp.testonline.sberbank.ru">
<externalOperationForm>true</externalOperationForm>
<newOperationsHistoryList>true</newOperationsHistoryList>
<hideDaySum>false</hideDaySum>
<tagAll>true</tagAll>
<additionalOperationForm>true</additionalOperationForm>
<logotypes>true</logotypes>
<routerForUFS>true</routerForUFS>
<replaceInvoicesToHistory>true</replaceInvoicesToHistory>
<receiveOperationsByTag>true</receiveOperationsByTag>
<replaceInvoicesToHistoryOnAccount>true</replaceInvoicesToHistoryOnAccount>
<refactoredOperationDetails>true</refactoredOperationDetails>
<smartSearchFromHistory>true</smartSearchFromHistory>
<referenceOnOperation>true</referenceOnOperation>
<logotypesInOperationDetails>true</logotypesInOperationDetails>
<arrestAndPunishmentOperations>true</arrestAndPunishmentOperations>
<mapInOperationDetails>true</mapInOperationDetails>
<advertisementInHistoryList>true</advertisementInHistoryList>
<extEpsPaymentOperation>true</extEpsPaymentOperation>
<hideExtEpsOperationRepeat>true</hideExtEpsOperationRepeat>
</node>
<node id="ift-node5-mp.testonline.sberbank.ru">
<externalOperationForm>true</externalOperationForm>
<newOperationsHistoryList>true</newOperationsHistoryList>
<hideDaySum>false</hideDaySum>
<tagAll>true</tagAll>
<additionalOperationForm>true</additionalOperationForm>
<logotypes>true</logotypes>
<routerForUFS>true</routerForUFS>
<replaceInvoicesToHistory>true</replaceInvoicesToHistory>
<receiveOperationsByTag>true</receiveOperationsByTag>
<replaceInvoicesToHistoryOnAccount>true</replaceInvoicesToHistoryOnAccount>
<refactoredOperationDetails>true</refactoredOperationDetails>
<smartSearchFromHistory>true</smartSearchFromHistory>
<referenceOnOperation>true</referenceOnOperation>
<logotypesInOperationDetails>true</logotypesInOperationDetails>
<arrestAndPunishmentOperations>true</arrestAndPunishmentOperations>
<mapInOperationDetails>true</mapInOperationDetails>
<advertisementInHistoryList>true</advertisementInHistoryList>
<extEpsPaymentOperation>true</extEpsPaymentOperation>
</node>
<node id="10.21.152.7">
<externalOperationForm>true</externalOperationForm>
<newOperationsHistoryList>true</newOperationsHistoryList>
<hideDaySum>false</hideDaySum>
<tagAll>true</tagAll>
<additionalOperationForm>true</additionalOperationForm>
<logotypes>true</logotypes>
<routerForUFS>true</routerForUFS>
<replaceInvoicesToHistory>true</replaceInvoicesToHistory>
<smartSearchFromHistory>true</smartSearchFromHistory>
<receiveOperationsByTag>true</receiveOperationsByTag>
<replaceInvoicesToHistoryOnAccount>true</replaceInvoicesToHistoryOnAccount>
<refactoredOperationDetails>true</refactoredOperationDetails>
<referenceOnOperation>true</referenceOnOperation>
<logotypesInOperationDetails>true</logotypesInOperationDetails>
<mapInOperationDetails>true</mapInOperationDetails>
<arrestAndPunishmentOperations>true</arrestAndPunishmentOperations>
<advertisementInHistoryList>true</advertisementInHistoryList>
<extEpsPaymentOperation>true</extEpsPaymentOperation>
</node>
</nodes>
</param>
<param name="DelayCuteCheck" description="время ожидания ответа с обогащённым контентом">
<type>setting</type>
<enabled>true</enabled>
<delay>20</delay>
</param>
<param name="TPNDataEnrichment" description="Возможность обогащения данных для ТПУ на разрешенных нодах">
<type>setting</type>
<enabled>true</enabled>
</param>
<param name="NodeTPNDataEnrichment" description="Возможность обогащения данных для ТПУ на разных нодах">
<type>list</type>
<nodes>
<node id="greenfield0.online.sberbank.ru">
<enabled>true</enabled>
</node>
<node id="greenfield1.online.sberbank.ru">
<enabled>true</enabled>
</node>
<node id="psinode1.testonline.sberbank.ru">
<enabled>true</enabled>
</node>
<node id="mobile.sberbank.ru">
<enabled>true</enabled>
</node>
<node id="194.186.207.23">
<enabled>true</enabled>
</node>
<node id="ift-node1.testonline.sberbank.ru">
<enabled>true</enabled>
</node>
<node id="ift-node2.testonline.sberbank.ru">
<enabled>true</enabled>
</node>
<node id="ift-node1-mp.testonline.sberbank.ru">
<enabled>true</enabled>
</node>
<node id="ift-node2-mp.testonline.sberbank.ru">
<enabled>true</enabled>
</node>
</nodes>
</param>
<param name="notificationStripeHistory" description="">
<type>setting</type>
<enabled>true</enabled>
<nodes>
<node id="node0.online.sberbank.ru">
<enabled>true</enabled>
</node>
<node id="greenfield0.online.sberbank.ru">
<enabled>true</enabled>
</node>
<node id="greenfield1.online.sberbank.ru">
<enabled>true</enabled>
</node>
<node id="psinode1.testonline.sberbank.ru">
<enabled>true</enabled>
</node>
<node id="mobile.sberbank.ru">
<enabled>true</enabled>
</node>
<node id="194.186.207.23">
<enabled>true</enabled>
</node>
<node id="ift-node1.testonline.sberbank.ru">
<enabled>true</enabled>
</node>
<node id="ift-node2.testonline.sberbank.ru">
<enabled>true</enabled>
</node>
<node id="ift-node1-mp.testonline.sberbank.ru">
<enabled>true</enabled>
</node>
<node id="ift-node2-mp.testonline.sberbank.ru">
<enabled>true</enabled>
</node>
</nodes>
</param>
<param name="notificationStripeFilter" description="">
<type>setting</type>
<enabled>true</enabled>
<nodes>
<node id="node0.online.sberbank.ru">
<enabled>true</enabled>
</node>
<node id="greenfield0.online.sberbank.ru">
<enabled>true</enabled>
</node>
<node id="greenfield1.online.sberbank.ru">
<enabled>true</enabled>
</node>
<node id="psinode1.testonline.sberbank.ru">
<enabled>true</enabled>
</node>
<node id="mobile.sberbank.ru">
<enabled>true</enabled>
</node>
<node id="194.186.207.23">
<enabled>true</enabled>
</node>
<node id="ift-node1.testonline.sberbank.ru">
<enabled>true</enabled>
</node>
<node id="ift-node2.testonline.sberbank.ru">
<enabled>true</enabled>
</node>
<node id="ift-node1-mp.testonline.sberbank.ru">
<enabled>true</enabled>
</node>
<node id="ift-node2-mp.testonline.sberbank.ru">
<enabled>true</enabled>
</node>
</nodes>
</param>
<param name="biometryAgreement" description="">
<type>list</type>
<enabled>true</enabled>
<showTutorial>false</showTutorial>
<nodes>
<node id="node0.online.sberbank.ru">
<enabled>false</enabled>
</node>
<node id="node1.online.sberbank.ru">
<enabled>false</enabled>
</node>
<node id="node2.online.sberbank.ru">
<enabled>false</enabled>
</node>
<node id="node3.online.sberbank.ru">
<enabled>true</enabled>
</node>
<node id="ift-node5-mp.testonline.sberbank.ru">
<enabled>true</enabled>
</node>
<node id="greenfield1.online.sberbank.ru">
<enabled>true</enabled>
</node>
<node id="194.186.207.23">
<enabled>true</enabled>
</node>
<node id="mobile.sberbank.ru">
<enabled>true</enabled>
</node>
<node id="ift-node1.testonline.sberbank.ru">
<enabled>true</enabled>
</node>
<node id="ift-node2.testonline.sberbank.ru">
<enabled>true</enabled>
</node>
<node id="ift-node1-mp.testonline.sberbank.ru">
<enabled>true</enabled>
</node>
<node id="ift-node2-mp.testonline.sberbank.ru">
<enabled>true</enabled>
</node>
</nodes>
</param>
<param name="NativeAppsCheck" description="">
<type>list</type>
<enabled>true</enabled>
<nodes>
<node id="node0.online.sberbank.ru">
<enabled>true</enabled>
</node>
<node id="node1.online.sberbank.ru">
<enabled>true</enabled>
</node>
<node id="node2.online.sberbank.ru">
<enabled>true</enabled>
</node>
<node id="node3.online.sberbank.ru">
<enabled>true</enabled>
</node>
<node id="ift-node5-mp.testonline.sberbank.ru">
<enabled>true</enabled>
</node>
<node id="greenfield1.online.sberbank.ru">
<enabled>true</enabled>
</node>
<node id="194.186.207.23">
<enabled>true</enabled>
</node>
<node id="mobile.sberbank.ru">
<enabled>true</enabled>
</node>
<node id="ift-node1.testonline.sberbank.ru">
<enabled>true</enabled>
</node>
<node id="ift-node2.testonline.sberbank.ru">
<enabled>true</enabled>
</node>
<node id="ift-node1-mp.testonline.sberbank.ru">
<enabled>true</enabled>
</node>
<node id="ift-node2-mp.testonline.sberbank.ru">
<enabled>true</enabled>
</node>
<node id="psinode2.testonline.sberbank.ru">
<enabled>true</enabled>
</node>
<node id="psinode1.testonline.sberbank.ru">
<enabled>true</enabled>
</node>
</nodes>
</param>
<param name="BiometricsTemplateCreate" description="">
<type>list</type>
<enabled>true</enabled>
<nodes>
<node id="node0.online.sberbank.ru">
<enabled>true</enabled>
</node>
<node id="node1.online.sberbank.ru">
<enabled>true</enabled>
</node>
<node id="node2.online.sberbank.ru">
<enabled>true</enabled>
</node>
<node id="node3.online.sberbank.ru">
<enabled>true</enabled>
</node>
<node id="ift-node5-mp.testonline.sberbank.ru">
<enabled>true</enabled>
</node>
<node id="greenfield1.online.sberbank.ru">
<enabled>true</enabled>
</node>
<node id="194.186.207.23">
<enabled>true</enabled>
</node>
<node id="mobile.sberbank.ru">
<enabled>true</enabled>
</node>
<node id="ift-node1.testonline.sberbank.ru">
<enabled>true</enabled>
</node>
<node id="ift-node2.testonline.sberbank.ru">
<enabled>true</enabled>
</node>
<node id="ift-node1-mp.testonline.sberbank.ru">
<enabled>true</enabled>
</node>
<node id="ift-node2-mp.testonline.sberbank.ru">
<enabled>true</enabled>
</node>
</nodes>
</param>
<param name="ConfirmationBiometricsVoice" description="">
<type>list</type>
<enabled>true</enabled>
<enabledInP2PTransfer>true</enabledInP2PTransfer>
<enabledInMessenger>true</enabledInMessenger>
<enabledInInternalPayments>true</enabledInInternalPayments>
<enabledInPayments>true</enabledInPayments>
<lightSchemeForMessenger>true</lightSchemeForMessenger>
<nodes>
<node id="node0.online.sberbank.ru">
<enabled>true</enabled>
<enabledInP2PTransfer>true</enabledInP2PTransfer>
<enabledInMessenger>true</enabledInMessenger>
<enabledInInternalPayments>true</enabledInInternalPayments>
<enabledInPayments>true</enabledInPayments>
<lightSchemeForMessenger>true</lightSchemeForMessenger>
</node>
<node id="node1.online.sberbank.ru">
<enabled>true</enabled>
<enabledInP2PTransfer>true</enabledInP2PTransfer>
<enabledInMessenger>true</enabledInMessenger>
<enabledInInternalPayments>true</enabledInInternalPayments>
<enabledInPayments>true</enabledInPayments>
<lightSchemeForMessenger>true</lightSchemeForMessenger>
</node>
<node id="node2.online.sberbank.ru">
<enabled>true</enabled>
<enabledInP2PTransfer>true</enabledInP2PTransfer>
<enabledInMessenger>true</enabledInMessenger>
<enabledInInternalPayments>true</enabledInInternalPayments>
<enabledInPayments>true</enabledInPayments>
<lightSchemeForMessenger>true</lightSchemeForMessenger>
</node>
<node id="node3.online.sberbank.ru">
<enabled>true</enabled>
<enabledInP2PTransfer>true</enabledInP2PTransfer>
<enabledInMessenger>true</enabledInMessenger>
<enabledInInternalPayments>true</enabledInInternalPayments>
<enabledInPayments>true</enabledInPayments>
<lightSchemeForMessenger>true</lightSchemeForMessenger>
</node>
<node id="ift-node5-mp.testonline.sberbank.ruu">
<enabled>true</enabled>
<enabledInP2PTransfer>true</enabledInP2PTransfer>
<enabledInMessenger>true</enabledInMessenger>
<enabledInInternalPayments>true</enabledInInternalPayments>
<enabledInPayments>true</enabledInPayments>
<lightSchemeForMessenger>true</lightSchemeForMessenger>
</node>
<node id="greenfield1.online.sberbank.ru">
<enabled>true</enabled>
<enabledInP2PTransfer>true</enabledInP2PTransfer>
<enabledInMessenger>true</enabledInMessenger>
<enabledInInternalPayments>true</enabledInInternalPayments>
<enabledInPayments>true</enabledInPayments>
<lightSchemeForMessenger>true</lightSchemeForMessenger>
</node>
<node id="mobile.sberbank.ru">
<enabled>true</enabled>
<enabledInP2PTransfer>true</enabledInP2PTransfer>
<enabledInMessenger>true</enabledInMessenger>
<enabledInInternalPayments>true</enabledInInternalPayments>
<enabledInPayments>true</enabledInPayments>
<lightSchemeForMessenger>true</lightSchemeForMessenger>
</node>
<node id="ift-node1.testonline.sberbank.ru">
<enabled>true</enabled>
<enabledInP2PTransfer>true</enabledInP2PTransfer>
<enabledInMessenger>true</enabledInMessenger>
<enabledInInternalPayments>true</enabledInInternalPayments>
<enabledInPayments>true</enabledInPayments>
<lightSchemeForMessenger>true</lightSchemeForMessenger>
</node>
<node id="ift-node2.testonline.sberbank.ru">
<enabled>true</enabled>
<enabledInP2PTransfer>true</enabledInP2PTransfer>
<enabledInMessenger>true</enabledInMessenger>
<enabledInInternalPayments>true</enabledInInternalPayments>
<enabledInPayments>true</enabledInPayments>
<lightSchemeForMessenger>true</lightSchemeForMessenger>
</node>
<node id="ift-node1-mp.testonline.sberbank.ru">
<enabled>true</enabled>
<enabledInP2PTransfer>true</enabledInP2PTransfer>
<enabledInMessenger>true</enabledInMessenger>
<enabledInInternalPayments>true</enabledInInternalPayments>
<enabledInPayments>true</enabledInPayments>
<lightSchemeForMessenger>true</lightSchemeForMessenger>
</node>
<node id="ift-node2-mp.testonline.sberbank.ru">
<enabled>true</enabled>
<enabledInP2PTransfer>true</enabledInP2PTransfer>
<enabledInMessenger>true</enabledInMessenger>
<enabledInInternalPayments>true</enabledInInternalPayments>
<enabledInPayments>true</enabledInPayments>
<lightSchemeForMessenger>true</lightSchemeForMessenger>
</node>
</nodes>
</param>
<param name="biometryAgreementStartPage" description="">
<type>list</type>
<enabled>true</enabled>
<nodes>
<node id="node0.online.sberbank.ru">
<enabled>true</enabled>
</node>
<node id="node1.online.sberbank.ru">
<enabled>true</enabled>
</node>
<node id="node2.online.sberbank.ru">
<enabled>true</enabled>
</node>
<node id="node3.online.sberbank.ru">
<enabled>true</enabled>
</node>
<node id="ift-node5-mp.testonline.sberbank.ru">
<enabled>true</enabled>
</node>
<node id="greenfield1.online.sberbank.ru">
<enabled>true</enabled>
</node>
<node id="194.186.207.23">
<enabled>true</enabled>
</node>
<node id="mobile.sberbank.ru">
<enabled>true</enabled>
</node>
<node id="ift-node1.testonline.sberbank.ru">
<enabled>true</enabled>
</node>
<node id="ift-node2.testonline.sberbank.ru">
<enabled>true</enabled>
</node>
<node id="ift-node1-mp.testonline.sberbank.ru">
<enabled>true</enabled>
</node>
<node id="ift-node2-mp.testonline.sberbank.ru">
<enabled>true</enabled>
</node>
</nodes>
</param>
<param name="BiometricsLivenessChecks" description="Настройки проверок на человечность в биометрических процессах">
<enabled>true</enabled>
<processes>
<process name="ConfirmationBiometrics">
<enabled>true</enabled>
<livenessType>BLINK</livenessType>
</process>
<process name="BiometricsTemplateCreate">
<enabled>true</enabled>
<livenessType>HEADMOVE|BLINK</livenessType>
</process>
</processes>
</param>
<param name="UFSWidgetConfirmationBiometrics" description="">
<type>list</type>
<enabled>true</enabled>
<nodes>
<node id="node0.online.sberbank.ru">
<enabled>true</enabled>
</node>
<node id="node1.online.sberbank.ru">
<enabled>true</enabled>
</node>
<node id="node2.online.sberbank.ru">
<enabled>true</enabled>
</node>
<node id="node3.online.sberbank.ru">
<enabled>true</enabled>
</node>
<node id="ift-node5-mp.testonline.sberbank.ru">
<enabled>true</enabled>
</node>
<node id="greenfield1.online.sberbank.ru">
<enabled>true</enabled>
</node>
<node id="194.186.207.23">
<enabled>true</enabled>
</node>
<node id="mobile.sberbank.ru">
<enabled>true</enabled>
</node>
<node id="ift-node1.testonline.sberbank.ru">
<enabled>true</enabled>
</node>
<node id="ift-node2.testonline.sberbank.ru">
<enabled>true</enabled>
</node>
<node id="ift-node1-mp.testonline.sberbank.ru">
<enabled>true</enabled>
</node>
<node id="ift-node2-mp.testonline.sberbank.ru">
<enabled>true</enabled>
</node>
</nodes>
</param>
<param name="LoanNavigationScreenEnabled" description="Разводной экран для кредитных продуктов">
<type>setting</type>
<enabled>true</enabled>
</param>
<param name="PushHistoryFastScroll" description="">
<type>setting</type>
<enabled>true</enabled>
</param>
<param name="SBOLBage" description="">
<type>setting</type>
<enabled>true</enabled>
<nodes>
<node id="mobile.sberbank.ru">
<enabled>true</enabled>
</node>
<node id="ift-node1.testonline.sberbank.ru">
<enabled>true</enabled>
</node>
<node id="ift-node2.testonline.sberbank.ru">
<enabled>true</enabled>
</node>
<node id="ift-node1-mp.testonline.sberbank.ru">
<enabled>true</enabled>
</node>
<node id="ift-node2-mp.testonline.sberbank.ru">
<enabled>true</enabled>
</node>
<node id="greenfield1.online.sberbank.ru">
<enabled>true</enabled>
</node>
</nodes>
<levels>
<level id="showAnimatedBagePostLoginHistory">
<enabled>true</enabled>
</level>
<level id="showBagePostLoginHistory">
<enabled>true</enabled>
</level>
<level id="showBagePreLogin">
<enabled>true</enabled>
</level>
<level id="showBageOnAppIcon">
<enabled>true</enabled>
</level>
<level id="showBadgePostLoginTabbar">
<enabled>true</enabled>
</level>
<level id="showBadgePostLoginNavBar">
<enabled>true</enabled>
</level>
</levels>
</param>
<param name="MAppDebitCardNegativeBalance" description="Почему минус на дебетовой карте">
<type>service</type>
<enabled>true</enabled>
<nodes>
<node id="node0.online.sberbank.ru">
<enabled>true</enabled>
</node>
<node id="node1.online.sberbank.ru">
<enabled>true</enabled>
</node>
<node id="node2.online.sberbank.ru">
<enabled>true</enabled>
</node>
<node id="node3.online.sberbank.ru">
<enabled>true</enabled>
</node>
<node id="greenfield1.online.sberbank.ru">
<enabled>true</enabled>
</node>
<node id="mobile.sberbank.ru">
<enabled>true</enabled>
</node>
<node id="ift-node1.testonline.sberbank.ru">
<enabled>true</enabled>
</node>
<node id="ift-node2.testonline.sberbank.ru">
<enabled>true</enabled>
</node>
<node id="ift-node1-mp.testonline.sberbank.ru">
<enabled>true</enabled>
</node>
<node id="ift-node2-mp.testonline.sberbank.ru">
<enabled>true</enabled>
</node>
<node id="psinode2.testonline.sberbank.ru">
<enabled>true</enabled>
</node>
<node id="psinode1.testonline.sberbank.ru">
<enabled>true</enabled>
</node>
<node id="194.186.207.23">
<enabled>true</enabled>
</node>
</nodes>
</param>
<param name="DepositsFlags" description="Вклады">
<type>list</type>
<enabled>true</enabled>
<minorsLimit>50000</minorsLimit>
<!--
 Настройка предупреждающих сообщений при разнице валют 
-->
<diffCurrencyTexts>
<diffCurrencyText id="Normal">
<DCWarningTitle>Не теряйте деньги на конвертации</DCWarningTitle>
<DCWarningText>
Валюты вклада и выбранного счёта не совпадают, поэтому перевод пройдёт с конвертацией по текущему курсу. Чтобы не терять деньги, выберите счёт в валюте вклада.
</DCWarningText>
<DCWarningOkButton>ПЕРЕВЕСТИ</DCWarningOkButton>
<DCWarningCancelButton>ВЫБРАТЬ ДРУГОЙ СЧЁТ</DCWarningCancelButton>
</diffCurrencyText>
<diffCurrencyText id="Pref">
<DCWarningTitle>Не теряйте деньги на конвертации</DCWarningTitle>
<DCWarningText>
Валюты вклада и выбранного счёта не совпадают, поэтому перевод пройдёт с конвертацией по льготному курсу. Чтобы не терять деньги, выберите счёт в валюте вклада.
</DCWarningText>
<DCWarningOkButton>ПЕРЕВЕСТИ</DCWarningOkButton>
<DCWarningCancelButton>ВЫБРАТЬ ДРУГОЙ СЧЁТ</DCWarningCancelButton>
</diffCurrencyText>
<diffCurrencyText id="Unknown">
<DCWarningTitle>Не теряйте деньги на конвертации</DCWarningTitle>
<DCWarningText>
Валюты вклада и выбранного счёта не совпадают, поэтому перевод пройдёт с конвертацией. Чтобы не терять деньги, выберите счёт в валюте вклада.
</DCWarningText>
<DCWarningOkButton>ПЕРЕВЕСТИ</DCWarningOkButton>
<DCWarningCancelButton>ВЫБРАТЬ ДРУГОЙ СЧЁТ</DCWarningCancelButton>
</diffCurrencyText>
</diffCurrencyTexts>
<nodes>
<!--
Смотрим на параметр amountPickerShowHintPopoverNew с версии 9.6
-->
<!--
Смотрим на параметр diffCurrencyWarning с версии 9.7
-->
<node id="mobile.sberbank.ru">
<minorsWarning>true</minorsWarning>
<autoSelectionForDepositTransferToResource>true</autoSelectionForDepositTransferToResource>
<amountPickerShowHintPopoverNew>false</amountPickerShowHintPopoverNew>
<diffCurrencyWarning>true</diffCurrencyWarning>
</node>
<node id="node0.online.sberbank.ru">
<minorsWarning>true</minorsWarning>
<autoSelectionForDepositTransferToResource>true</autoSelectionForDepositTransferToResource>
<amountPickerShowHintPopoverNew>true</amountPickerShowHintPopoverNew>
<diffCurrencyWarning>true</diffCurrencyWarning>
</node>
<node id="node1.online.sberbank.ru">
<minorsWarning>true</minorsWarning>
<autoSelectionForDepositTransferToResource>true</autoSelectionForDepositTransferToResource>
<amountPickerShowHintPopoverNew>true</amountPickerShowHintPopoverNew>
<diffCurrencyWarning>true</diffCurrencyWarning>
</node>
<node id="node2.online.sberbank.ru">
<minorsWarning>true</minorsWarning>
<autoSelectionForDepositTransferToResource>true</autoSelectionForDepositTransferToResource>
<amountPickerShowHintPopoverNew>true</amountPickerShowHintPopoverNew>
<diffCurrencyWarning>true</diffCurrencyWarning>
</node>
<node id="node3.online.sberbank.ru">
<minorsWarning>true</minorsWarning>
<autoSelectionForDepositTransferToResource>true</autoSelectionForDepositTransferToResource>
<amountPickerShowHintPopoverNew>true</amountPickerShowHintPopoverNew>
<diffCurrencyWarning>true</diffCurrencyWarning>
</node>
<node id="node4.online.sberbank.ru">
<minorsWarning>true</minorsWarning>
<autoSelectionForDepositTransferToResource>true</autoSelectionForDepositTransferToResource>
<amountPickerShowHintPopoverNew>true</amountPickerShowHintPopoverNew>
<diffCurrencyWarning>true</diffCurrencyWarning>
</node>
<node id="greenfield1.online.sberbank.ru">
<minorsWarning>true</minorsWarning>
<autoSelectionForDepositTransferToResource>true</autoSelectionForDepositTransferToResource>
<amountPickerShowHintPopoverNew>true</amountPickerShowHintPopoverNew>
<diffCurrencyWarning>true</diffCurrencyWarning>
</node>
<node id="greenfield2.online.sberbank.ru">
<minorsWarning>true</minorsWarning>
<autoSelectionForDepositTransferToResource>true</autoSelectionForDepositTransferToResource>
<amountPickerShowHintPopoverNew>true</amountPickerShowHintPopoverNew>
<diffCurrencyWarning>true</diffCurrencyWarning>
</node>
<node id="ift-node0-mp.testonline.sberbank.ru">
<minorsWarning>true</minorsWarning>
<autoSelectionForDepositTransferToResource>true</autoSelectionForDepositTransferToResource>
<amountPickerShowHintPopoverNew>true</amountPickerShowHintPopoverNew>
<diffCurrencyWarning>true</diffCurrencyWarning>
</node>
<node id="ift-node1-mp.testonline.sberbank.ru">
<minorsWarning>true</minorsWarning>
<autoSelectionForDepositTransferToResource>true</autoSelectionForDepositTransferToResource>
<amountPickerShowHintPopoverNew>true</amountPickerShowHintPopoverNew>
<diffCurrencyWarning>true</diffCurrencyWarning>
</node>
<node id="ift-node2-mp.testonline.sberbank.ru">
<minorsWarning>true</minorsWarning>
<autoSelectionForDepositTransferToResource>true</autoSelectionForDepositTransferToResource>
<amountPickerShowHintPopoverNew>true</amountPickerShowHintPopoverNew>
<diffCurrencyWarning>true</diffCurrencyWarning>
</node>
<node id="ift-node3-mp.testonline.sberbank.ru">
<minorsWarning>true</minorsWarning>
<autoSelectionForDepositTransferToResource>true</autoSelectionForDepositTransferToResource>
<amountPickerShowHintPopoverNew>true</amountPickerShowHintPopoverNew>
<diffCurrencyWarning>true</diffCurrencyWarning>
</node>
<node id="ift-node4-mp.testonline.sberbank.ru">
<minorsWarning>true</minorsWarning>
<autoSelectionForDepositTransferToResource>true</autoSelectionForDepositTransferToResource>
<amountPickerShowHintPopoverNew>true</amountPickerShowHintPopoverNew>
<diffCurrencyWarning>true</diffCurrencyWarning>
</node>
<node id="psinode1.testonline.sberbank.ru">
<minorsWarning>true</minorsWarning>
<autoSelectionForDepositTransferToResource>true</autoSelectionForDepositTransferToResource>
<amountPickerShowHintPopoverNew>true</amountPickerShowHintPopoverNew>
<diffCurrencyWarning>true</diffCurrencyWarning>
</node>
<node id="psinode2.testonline.sberbank.ru">
<minorsWarning>true</minorsWarning>
<autoSelectionForDepositTransferToResource>true</autoSelectionForDepositTransferToResource>
<amountPickerShowHintPopoverNew>true</amountPickerShowHintPopoverNew>
<diffCurrencyWarning>true</diffCurrencyWarning>
</node>
</nodes>
</param>
<param name="DepositsSliderMaxValue" description="Изменение правой границы бегунка суммовой градации во вкладах">
<type>list</type>
<enabled>true</enabled>
<nodes>
<node id="mobile.sberbank.ru">
<enabled>true</enabled>
</node>
<node id="node0.online.sberbank.ru">
<enabled>true</enabled>
</node>
<node id="node1.online.sberbank.ru">
<enabled>true</enabled>
</node>
<node id="node2.online.sberbank.ru">
<enabled>true</enabled>
</node>
<node id="node3.online.sberbank.ru">
<enabled>true</enabled>
</node>
<node id="node4.online.sberbank.ru">
<enabled>true</enabled>
</node>
<node id="greenfield1.online.sberbank.ru">
<enabled>true</enabled>
</node>
<node id="greenfield2.online.sberbank.ru">
<enabled>true</enabled>
</node>
<node id="ift-node1-mp.testonline.sberbank.ru">
<enabled>true</enabled>
</node>
<node id="ift-node2-mp.testonline.sberbank.ru">
<enabled>true</enabled>
</node>
<node id="psinode2.testonline.sberbank.ru">
<enabled>true</enabled>
</node>
<node id="psinode1.testonline.sberbank.ru">
<enabled>true</enabled>
</node>
</nodes>
</param>
<param name="PromoCodeActivation" description="Ввод промо-кодов для вкладов">
<type>setting</type>
<enabled>true</enabled>
</param>
<param name="SaveUserSelectionParameters" description="Пакет улучшений клиентского опыта по открытию вкладов">
<type>list</type>
<enabled>true</enabled>
<nodes>
<node id="mobile.sberbank.ru">
<enabled>true</enabled>
</node>
<node id="node0.online.sberbank.ru">
<enabled>true</enabled>
</node>
<node id="node1.online.sberbank.ru">
<enabled>true</enabled>
</node>
<node id="node2.online.sberbank.ru">
<enabled>true</enabled>
</node>
<node id="node3.online.sberbank.ru">
<enabled>true</enabled>
</node>
<node id="node4.online.sberbank.ru">
<enabled>true</enabled>
</node>
<node id="greenfield1.online.sberbank.ru">
<enabled>true</enabled>
</node>
<node id="greenfield2.online.sberbank.ru">
<enabled>true</enabled>
</node>
<node id="ift-node1-mp.testonline.sberbank.ru">
<enabled>true</enabled>
</node>
<node id="ift-node2-mp.testonline.sberbank.ru">
<enabled>true</enabled>
</node>
<node id="psinode2.testonline.sberbank.ru">
<enabled>true</enabled>
</node>
<node id="psinode1.testonline.sberbank.ru">
<enabled>true</enabled>
</node>
</nodes>
</param>
<param name="CollapseDepositsOfSameType" description="Оптимизация отображения вкладов, доступных для открытия">
<type>list</type>
<enabled>true</enabled>
<nodes>
<node id="mobile.sberbank.ru">
<enabled>true</enabled>
</node>
<node id="node0.online.sberbank.ru">
<enabled>true</enabled>
</node>
<node id="node1.online.sberbank.ru">
<enabled>true</enabled>
</node>
<node id="node2.online.sberbank.ru">
<enabled>true</enabled>
</node>
<node id="node3.online.sberbank.ru">
<enabled>true</enabled>
</node>
<node id="node4.online.sberbank.ru">
<enabled>true</enabled>
</node>
<node id="greenfield1.online.sberbank.ru">
<enabled>true</enabled>
</node>
<node id="greenfield2.online.sberbank.ru">
<enabled>true</enabled>
</node>
<node id="ift-node1-mp.testonline.sberbank.ru">
<enabled>true</enabled>
</node>
<node id="ift-node2-mp.testonline.sberbank.ru">
<enabled>true</enabled>
</node>
<node id="psinode2.testonline.sberbank.ru">
<enabled>true</enabled>
</node>
<node id="psinode1.testonline.sberbank.ru">
<enabled>true</enabled>
</node>
</nodes>
</param>
<param name="CollapseDepositsOfSameTypeWithoutDistinctUnion" description="Изменение отображения Условий вклада при открытии">
<type>list</type>
<enabled>true</enabled>
<nodes>
<node id="mobile.sberbank.ru">
<enabled>true</enabled>
</node>
<node id="node0.online.sberbank.ru">
<enabled>true</enabled>
</node>
<node id="node1.online.sberbank.ru">
<enabled>true</enabled>
</node>
<node id="node2.online.sberbank.ru">
<enabled>true</enabled>
</node>
<node id="node3.online.sberbank.ru">
<enabled>true</enabled>
</node>
<node id="node4.online.sberbank.ru">
<enabled>true</enabled>
</node>
<node id="greenfield1.online.sberbank.ru">
<enabled>true</enabled>
</node>
<node id="greenfield2.online.sberbank.ru">
<enabled>true</enabled>
</node>
<node id="ift-node1-mp.testonline.sberbank.ru">
<enabled>true</enabled>
</node>
<node id="ift-node2-mp.testonline.sberbank.ru">
<enabled>true</enabled>
</node>
<node id="psinode2.testonline.sberbank.ru">
<enabled>true</enabled>
</node>
<node id="psinode1.testonline.sberbank.ru">
<enabled>true</enabled>
</node>
</nodes>
</param>
<param name="SmartDepositDatePicker" description="Изменение работы инструмента выбора срока вклада">
<type>list</type>
<enabled>true</enabled>
<nodes>
<node id="mobile.sberbank.ru">
<enabled>true</enabled>
</node>
<node id="node0.online.sberbank.ru">
<enabled>true</enabled>
</node>
<node id="node1.online.sberbank.ru">
<enabled>true</enabled>
</node>
<node id="node2.online.sberbank.ru">
<enabled>true</enabled>
</node>
<node id="node3.online.sberbank.ru">
<enabled>true</enabled>
</node>
<node id="node4.online.sberbank.ru">
<enabled>true</enabled>
</node>
<node id="greenfield1.online.sberbank.ru">
<enabled>true</enabled>
</node>
<node id="greenfield2.online.sberbank.ru">
<enabled>true</enabled>
</node>
<node id="ift-node1-mp.testonline.sberbank.ru">
<enabled>true</enabled>
</node>
<node id="ift-node2-mp.testonline.sberbank.ru">
<enabled>true</enabled>
</node>
<node id="psinode2.testonline.sberbank.ru">
<enabled>true</enabled>
</node>
<node id="psinode1.testonline.sberbank.ru">
<enabled>true</enabled>
</node>
</nodes>
</param>
<!--
Смотрим на параметр AmountPickerShowHintPopover в версии 9.5
-->
<param name="AmountPickerShowHintPopover" description="Облако с подсказкой о том, что большую сумму можно ввести руками">
<type>list</type>
<enabled>true</enabled>
<nodes>
<node id="mobile.sberbank.ru">
<enabled>true</enabled>
</node>
<node id="node0.online.sberbank.ru">
<enabled>true</enabled>
</node>
<node id="node1.online.sberbank.ru">
<enabled>true</enabled>
</node>
<node id="node2.online.sberbank.ru">
<enabled>true</enabled>
</node>
<node id="node3.online.sberbank.ru">
<enabled>true</enabled>
</node>
<node id="node4.online.sberbank.ru">
<enabled>true</enabled>
</node>
<node id="greenfield1.online.sberbank.ru">
<enabled>true</enabled>
</node>
<node id="greenfield2.online.sberbank.ru">
<enabled>true</enabled>
</node>
<node id="ift-node1-mp.testonline.sberbank.ru">
<enabled>true</enabled>
</node>
<node id="ift-node2-mp.testonline.sberbank.ru">
<enabled>true</enabled>
</node>
<node id="psinode2.testonline.sberbank.ru">
<enabled>true</enabled>
</node>
<node id="psinode1.testonline.sberbank.ru">
<enabled>true</enabled>
</node>
</nodes>
</param>
<param name="PriorityCardP2PService" description="Установка приоритетной карты для зачисления P2P Переводов по НМТ">
<type>setting</type>
<enabled>true</enabled>
</param>
<param name="PriorityCardP2PServiceTutorial" description="Туториал для приоритетной карты">
<type>setting</type>
<enabled>true</enabled>
</param>
<param name="PushPermissions" description="единый стек параметров для push">
<type>list</type>
<nodes>
<node id="greenfield0.online.sberbank.ru">
<buttonToPostLogin>true</buttonToPostLogin>
<pushHistoryAvailableInTabbarBank>true</pushHistoryAvailableInTabbarBank>
<MFMSMessageRequestType>2</MFMSMessageRequestType>
<NotificationSettingsOwn>true</NotificationSettingsOwn>
<autoTurnOffOperationPush>true</autoTurnOffOperationPush>
<TurnOffOperationPush>true</TurnOffOperationPush>
<MessagesWithExpired>true</MessagesWithExpired>
<showBestActionsInCuteCheque>true</showBestActionsInCuteCheque>
<showNotificationEntryPointTargetTapPrelogin>true</showNotificationEntryPointTargetTapPrelogin>
<showNotificationEntryPointTargetTapPostlogin>true</showNotificationEntryPointTargetTapPostlogin>
<newRejectAuthorizeAlert>true</newRejectAuthorizeAlert>
<showAlertBeforeTPUDisable>true</showAlertBeforeTPUDisable>
<showUniversalPushNotification>true</showUniversalPushNotification>
<getMessageHistoryRequestEnabled>true</getMessageHistoryRequestEnabled>
<nativePushProcessingEnabled>true</nativePushProcessingEnabled>
<webUrlInUniversalPushNotification>true</webUrlInUniversalPushNotification>
<cardNotificationWithSenderNameAndComment>true</cardNotificationWithSenderNameAndComment>
<routingFromTransactionPushToMessengerEnabled>true</routingFromTransactionPushToMessengerEnabled>
<pushLogoTypeUsing>true</pushLogoTypeUsing>
<UsePushAutoDisable>true</UsePushAutoDisable>
<reactivateMainPushNotifications>true</reactivateMainPushNotifications>
<hideMainPushNotificationsSwitcher>true</hideMainPushNotificationsSwitcher>
</node>
<node id="greenfield1.online.sberbank.ru">
<buttonToPostLogin>true</buttonToPostLogin>
<pushHistoryAvailableInTabbarBank>true</pushHistoryAvailableInTabbarBank>
<MFMSMessageRequestType>2</MFMSMessageRequestType>
<NotificationSettingsOwn>true</NotificationSettingsOwn>
<autoTurnOffOperationPush>true</autoTurnOffOperationPush>
<TurnOffOperationPush>true</TurnOffOperationPush>
<MessagesWithExpired>true</MessagesWithExpired>
<showBestActionsInCuteCheque>true</showBestActionsInCuteCheque>
<showNotificationEntryPointTargetTapPrelogin>true</showNotificationEntryPointTargetTapPrelogin>
<showNotificationEntryPointTargetTapPostlogin>true</showNotificationEntryPointTargetTapPostlogin>
<newRejectAuthorizeAlert>true</newRejectAuthorizeAlert>
<showAlertBeforeTPUDisable>true</showAlertBeforeTPUDisable>
<showUniversalPushNotification>true</showUniversalPushNotification>
<getMessageHistoryRequestEnabled>true</getMessageHistoryRequestEnabled>
<nativePushProcessingEnabled>true</nativePushProcessingEnabled>
<webUrlInUniversalPushNotification>true</webUrlInUniversalPushNotification>
<cardNotificationWithSenderNameAndComment>true</cardNotificationWithSenderNameAndComment>
<routingFromTransactionPushToMessengerEnabled>true</routingFromTransactionPushToMessengerEnabled>
<pushLogoTypeUsing>true</pushLogoTypeUsing>
<UsePushAutoDisable>true</UsePushAutoDisable>
<reactivateMainPushNotifications>true</reactivateMainPushNotifications>
<hideMainPushNotificationsSwitcher>true</hideMainPushNotificationsSwitcher>
</node>
<node id="node0.online.sberbank.ru">
<buttonToPostLogin>true</buttonToPostLogin>
<pushHistoryAvailableInTabbarBank>true</pushHistoryAvailableInTabbarBank>
<MFMSMessageRequestType>2</MFMSMessageRequestType>
<NotificationSettingsOwn>true</NotificationSettingsOwn>
<autoTurnOffOperationPush>true</autoTurnOffOperationPush>
<TurnOffOperationPush>true</TurnOffOperationPush>
<MessagesWithExpired>true</MessagesWithExpired>
<showBestActionsInCuteCheque>true</showBestActionsInCuteCheque>
<showNotificationEntryPointTargetTapPrelogin>true</showNotificationEntryPointTargetTapPrelogin>
<showNotificationEntryPointTargetTapPostlogin>true</showNotificationEntryPointTargetTapPostlogin>
<newRejectAuthorizeAlert>true</newRejectAuthorizeAlert>
<showAlertBeforeTPUDisable>true</showAlertBeforeTPUDisable>
<showUniversalPushNotification>true</showUniversalPushNotification>
<getMessageHistoryRequestEnabled>true</getMessageHistoryRequestEnabled>
<nativePushProcessingEnabled>true</nativePushProcessingEnabled>
<webUrlInUniversalPushNotification>true</webUrlInUniversalPushNotification>
<cardNotificationWithSenderNameAndComment>true</cardNotificationWithSenderNameAndComment>
<routingFromTransactionPushToMessengerEnabled>true</routingFromTransactionPushToMessengerEnabled>
<pushLogoTypeUsing>true</pushLogoTypeUsing>
<UsePushAutoDisable>true</UsePushAutoDisable>
<reactivateMainPushNotifications>true</reactivateMainPushNotifications>
<hideMainPushNotificationsSwitcher>true</hideMainPushNotificationsSwitcher>
</node>
<node id="node1.online.sberbank.ru">
<buttonToPostLogin>true</buttonToPostLogin>
<pushHistoryAvailableInTabbarBank>true</pushHistoryAvailableInTabbarBank>
<MFMSMessageRequestType>2</MFMSMessageRequestType>
<NotificationSettingsOwn>true</NotificationSettingsOwn>
<autoTurnOffOperationPush>true</autoTurnOffOperationPush>
<TurnOffOperationPush>true</TurnOffOperationPush>
<MessagesWithExpired>true</MessagesWithExpired>
<showBestActionsInCuteCheque>true</showBestActionsInCuteCheque>
<showNotificationEntryPointTargetTapPrelogin>true</showNotificationEntryPointTargetTapPrelogin>
<showNotificationEntryPointTargetTapPostlogin>true</showNotificationEntryPointTargetTapPostlogin>
<newRejectAuthorizeAlert>true</newRejectAuthorizeAlert>
<showAlertBeforeTPUDisable>true</showAlertBeforeTPUDisable>
<showUniversalPushNotification>true</showUniversalPushNotification>
<getMessageHistoryRequestEnabled>true</getMessageHistoryRequestEnabled>
<nativePushProcessingEnabled>true</nativePushProcessingEnabled>
<webUrlInUniversalPushNotification>true</webUrlInUniversalPushNotification>
<cardNotificationWithSenderNameAndComment>true</cardNotificationWithSenderNameAndComment>
<routingFromTransactionPushToMessengerEnabled>true</routingFromTransactionPushToMessengerEnabled>
<pushLogoTypeUsing>true</pushLogoTypeUsing>
<UsePushAutoDisable>true</UsePushAutoDisable>
<reactivateMainPushNotifications>true</reactivateMainPushNotifications>
<hideMainPushNotificationsSwitcher>true</hideMainPushNotificationsSwitcher>
</node>
<node id="node2.online.sberbank.ru">
<buttonToPostLogin>true</buttonToPostLogin>
<pushHistoryAvailableInTabbarBank>true</pushHistoryAvailableInTabbarBank>
<MFMSMessageRequestType>2</MFMSMessageRequestType>
<NotificationSettingsOwn>true</NotificationSettingsOwn>
<autoTurnOffOperationPush>true</autoTurnOffOperationPush>
<TurnOffOperationPush>true</TurnOffOperationPush>
<MessagesWithExpired>true</MessagesWithExpired>
<showBestActionsInCuteCheque>true</showBestActionsInCuteCheque>
<showNotificationEntryPointTargetTapPrelogin>true</showNotificationEntryPointTargetTapPrelogin>
<showNotificationEntryPointTargetTapPostlogin>true</showNotificationEntryPointTargetTapPostlogin>
<newRejectAuthorizeAlert>true</newRejectAuthorizeAlert>
<showAlertBeforeTPUDisable>true</showAlertBeforeTPUDisable>
<showUniversalPushNotification>true</showUniversalPushNotification>
<getMessageHistoryRequestEnabled>true</getMessageHistoryRequestEnabled>
<nativePushProcessingEnabled>true</nativePushProcessingEnabled>
<webUrlInUniversalPushNotification>true</webUrlInUniversalPushNotification>
<cardNotificationWithSenderNameAndComment>true</cardNotificationWithSenderNameAndComment>
<routingFromTransactionPushToMessengerEnabled>true</routingFromTransactionPushToMessengerEnabled>
<pushLogoTypeUsing>true</pushLogoTypeUsing>
<UsePushAutoDisable>true</UsePushAutoDisable>
<reactivateMainPushNotifications>true</reactivateMainPushNotifications>
<hideMainPushNotificationsSwitcher>true</hideMainPushNotificationsSwitcher>
</node>
<node id="node3.online.sberbank.ru">
<buttonToPostLogin>true</buttonToPostLogin>
<pushHistoryAvailableInTabbarBank>true</pushHistoryAvailableInTabbarBank>
<MFMSMessageRequestType>2</MFMSMessageRequestType>
<NotificationSettingsOwn>true</NotificationSettingsOwn>
<autoTurnOffOperationPush>true</autoTurnOffOperationPush>
<TurnOffOperationPush>true</TurnOffOperationPush>
<MessagesWithExpired>true</MessagesWithExpired>
<showBestActionsInCuteCheque>true</showBestActionsInCuteCheque>
<showNotificationEntryPointTargetTapPrelogin>true</showNotificationEntryPointTargetTapPrelogin>
<showNotificationEntryPointTargetTapPostlogin>true</showNotificationEntryPointTargetTapPostlogin>
<newRejectAuthorizeAlert>true</newRejectAuthorizeAlert>
<showAlertBeforeTPUDisable>true</showAlertBeforeTPUDisable>
<showUniversalPushNotification>true</showUniversalPushNotification>
<getMessageHistoryRequestEnabled>true</getMessageHistoryRequestEnabled>
<nativePushProcessingEnabled>true</nativePushProcessingEnabled>
<webUrlInUniversalPushNotification>true</webUrlInUniversalPushNotification>
<cardNotificationWithSenderNameAndComment>true</cardNotificationWithSenderNameAndComment>
<routingFromTransactionPushToMessengerEnabled>true</routingFromTransactionPushToMessengerEnabled>
<pushLogoTypeUsing>true</pushLogoTypeUsing>
<UsePushAutoDisable>true</UsePushAutoDisable>
<reactivateMainPushNotifications>true</reactivateMainPushNotifications>
<hideMainPushNotificationsSwitcher>true</hideMainPushNotificationsSwitcher>
</node>
<node id="node4.online.sberbank.ru">
<buttonToPostLogin>true</buttonToPostLogin>
<pushHistoryAvailableInTabbarBank>true</pushHistoryAvailableInTabbarBank>
<MFMSMessageRequestType>2</MFMSMessageRequestType>
<NotificationSettingsOwn>true</NotificationSettingsOwn>
<autoTurnOffOperationPush>true</autoTurnOffOperationPush>
<TurnOffOperationPush>true</TurnOffOperationPush>
<MessagesWithExpired>true</MessagesWithExpired>
<showBestActionsInCuteCheque>true</showBestActionsInCuteCheque>
<showNotificationEntryPointTargetTapPrelogin>true</showNotificationEntryPointTargetTapPrelogin>
<showNotificationEntryPointTargetTapPostlogin>true</showNotificationEntryPointTargetTapPostlogin>
<newRejectAuthorizeAlert>true</newRejectAuthorizeAlert>
<showAlertBeforeTPUDisable>true</showAlertBeforeTPUDisable>
<showUniversalPushNotification>true</showUniversalPushNotification>
<getMessageHistoryRequestEnabled>true</getMessageHistoryRequestEnabled>
<nativePushProcessingEnabled>true</nativePushProcessingEnabled>
<webUrlInUniversalPushNotification>true</webUrlInUniversalPushNotification>
<cardNotificationWithSenderNameAndComment>true</cardNotificationWithSenderNameAndComment>
<routingFromTransactionPushToMessengerEnabled>true</routingFromTransactionPushToMessengerEnabled>
<pushLogoTypeUsing>true</pushLogoTypeUsing>
<UsePushAutoDisable>true</UsePushAutoDisable>
<reactivateMainPushNotifications>true</reactivateMainPushNotifications>
<hideMainPushNotificationsSwitcher>true</hideMainPushNotificationsSwitcher>
</node>
<node id="psinode1.testonline.sberbank.ru">
<buttonToPostLogin>true</buttonToPostLogin>
<pushHistoryAvailableInTabbarBank>true</pushHistoryAvailableInTabbarBank>
<MFMSMessageRequestType>2</MFMSMessageRequestType>
<NotificationSettingsOwn>true</NotificationSettingsOwn>
<autoTurnOffOperationPush>true</autoTurnOffOperationPush>
<TurnOffOperationPush>true</TurnOffOperationPush>
<MessagesWithExpired>true</MessagesWithExpired>
<showBestActionsInCuteCheque>true</showBestActionsInCuteCheque>
<showNotificationEntryPointTargetTapPrelogin>true</showNotificationEntryPointTargetTapPrelogin>
<showNotificationEntryPointTargetTapPostlogin>true</showNotificationEntryPointTargetTapPostlogin>
<newRejectAuthorizeAlert>true</newRejectAuthorizeAlert>
<showAlertBeforeTPUDisable>true</showAlertBeforeTPUDisable>
<showUniversalPushNotification>true</showUniversalPushNotification>
<getMessageHistoryRequestEnabled>true</getMessageHistoryRequestEnabled>
<nativePushProcessingEnabled>true</nativePushProcessingEnabled>
<webUrlInUniversalPushNotification>true</webUrlInUniversalPushNotification>
<cardNotificationWithSenderNameAndComment>true</cardNotificationWithSenderNameAndComment>
<routingFromTransactionPushToMessengerEnabled>true</routingFromTransactionPushToMessengerEnabled>
<pushLogoTypeUsing>true</pushLogoTypeUsing>
<UsePushAutoDisable>true</UsePushAutoDisable>
<reactivateMainPushNotifications>true</reactivateMainPushNotifications>
<hideMainPushNotificationsSwitcher>true</hideMainPushNotificationsSwitcher>
</node>
<node id="mobile.sberbank.ru">
<buttonToPostLogin>true</buttonToPostLogin>
<pushHistoryAvailableInTabbarBank>true</pushHistoryAvailableInTabbarBank>
<MFMSMessageRequestType>2</MFMSMessageRequestType>
<NotificationSettingsOwn>true</NotificationSettingsOwn>
<autoTurnOffOperationPush>true</autoTurnOffOperationPush>
<TurnOffOperationPush>true</TurnOffOperationPush>
<MessagesWithExpired>true</MessagesWithExpired>
<showBestActionsInCuteCheque>true</showBestActionsInCuteCheque>
<showNotificationEntryPointTargetTapPrelogin>true</showNotificationEntryPointTargetTapPrelogin>
<showNotificationEntryPointTargetTapPostlogin>true</showNotificationEntryPointTargetTapPostlogin>
<newRejectAuthorizeAlert>true</newRejectAuthorizeAlert>
<showAlertBeforeTPUDisable>true</showAlertBeforeTPUDisable>
<showUniversalPushNotification>true</showUniversalPushNotification>
<getMessageHistoryRequestEnabled>true</getMessageHistoryRequestEnabled>
<nativePushProcessingEnabled>true</nativePushProcessingEnabled>
<webUrlInUniversalPushNotification>true</webUrlInUniversalPushNotification>
<cardNotificationWithSenderNameAndComment>true</cardNotificationWithSenderNameAndComment>
<routingFromTransactionPushToMessengerEnabled>true</routingFromTransactionPushToMessengerEnabled>
<pushLogoTypeUsing>true</pushLogoTypeUsing>
<UsePushAutoDisable>true</UsePushAutoDisable>
<reactivateMainPushNotifications>true</reactivateMainPushNotifications>
<hideMainPushNotificationsSwitcher>true</hideMainPushNotificationsSwitcher>
</node>
<node id="194.186.207.23">
<buttonToPostLogin>true</buttonToPostLogin>
<pushHistoryAvailableInTabbarBank>true</pushHistoryAvailableInTabbarBank>
<MFMSMessageRequestType>2</MFMSMessageRequestType>
<NotificationSettingsOwn>true</NotificationSettingsOwn>
<autoTurnOffOperationPush>true</autoTurnOffOperationPush>
<TurnOffOperationPush>true</TurnOffOperationPush>
<MessagesWithExpired>true</MessagesWithExpired>
<showBestActionsInCuteCheque>true</showBestActionsInCuteCheque>
<showNotificationEntryPointTargetTapPrelogin>true</showNotificationEntryPointTargetTapPrelogin>
<showNotificationEntryPointTargetTapPostlogin>true</showNotificationEntryPointTargetTapPostlogin>
<newRejectAuthorizeAlert>true</newRejectAuthorizeAlert>
<showAlertBeforeTPUDisable>true</showAlertBeforeTPUDisable>
<showUniversalPushNotification>true</showUniversalPushNotification>
<getMessageHistoryRequestEnabled>true</getMessageHistoryRequestEnabled>
<nativePushProcessingEnabled>true</nativePushProcessingEnabled>
<webUrlInUniversalPushNotification>true</webUrlInUniversalPushNotification>
<cardNotificationWithSenderNameAndComment>true</cardNotificationWithSenderNameAndComment>
<routingFromTransactionPushToMessengerEnabled>true</routingFromTransactionPushToMessengerEnabled>
<pushLogoTypeUsing>true</pushLogoTypeUsing>
<UsePushAutoDisable>true</UsePushAutoDisable>
<reactivateMainPushNotifications>true</reactivateMainPushNotifications>
<hideMainPushNotificationsSwitcher>true</hideMainPushNotificationsSwitcher>
</node>
<node id="ift-node1.testonline.sberbank.ru">
<buttonToPostLogin>true</buttonToPostLogin>
<pushHistoryAvailableInTabbarBank>true</pushHistoryAvailableInTabbarBank>
<MFMSMessageRequestType>2</MFMSMessageRequestType>
<NotificationSettingsOwn>true</NotificationSettingsOwn>
<autoTurnOffOperationPush>true</autoTurnOffOperationPush>
<TurnOffOperationPush>true</TurnOffOperationPush>
<MessagesWithExpired>true</MessagesWithExpired>
<showBestActionsInCuteCheque>true</showBestActionsInCuteCheque>
<showNotificationEntryPointTargetTapPrelogin>true</showNotificationEntryPointTargetTapPrelogin>
<showNotificationEntryPointTargetTapPostlogin>true</showNotificationEntryPointTargetTapPostlogin>
<newRejectAuthorizeAlert>true</newRejectAuthorizeAlert>
<showAlertBeforeTPUDisable>true</showAlertBeforeTPUDisable>
<showUniversalPushNotification>true</showUniversalPushNotification>
<getMessageHistoryRequestEnabled>true</getMessageHistoryRequestEnabled>
<nativePushProcessingEnabled>true</nativePushProcessingEnabled>
<webUrlInUniversalPushNotification>true</webUrlInUniversalPushNotification>
<cardNotificationWithSenderNameAndComment>true</cardNotificationWithSenderNameAndComment>
<routingFromTransactionPushToMessengerEnabled>true</routingFromTransactionPushToMessengerEnabled>
<pushLogoTypeUsing>true</pushLogoTypeUsing>
<UsePushAutoDisable>true</UsePushAutoDisable>
<reactivateMainPushNotifications>true</reactivateMainPushNotifications>
<hideMainPushNotificationsSwitcher>true</hideMainPushNotificationsSwitcher>
</node>
<node id="ift-node2.testonline.sberbank.ru">
<buttonToPostLogin>true</buttonToPostLogin>
<pushHistoryAvailableInTabbarBank>true</pushHistoryAvailableInTabbarBank>
<MFMSMessageRequestType>2</MFMSMessageRequestType>
<NotificationSettingsOwn>true</NotificationSettingsOwn>
<autoTurnOffOperationPush>true</autoTurnOffOperationPush>
<TurnOffOperationPush>true</TurnOffOperationPush>
<MessagesWithExpired>true</MessagesWithExpired>
<showBestActionsInCuteCheque>true</showBestActionsInCuteCheque>
<showNotificationEntryPointTargetTapPrelogin>true</showNotificationEntryPointTargetTapPrelogin>
<showNotificationEntryPointTargetTapPostlogin>true</showNotificationEntryPointTargetTapPostlogin>
<newRejectAuthorizeAlert>true</newRejectAuthorizeAlert>
<showAlertBeforeTPUDisable>true</showAlertBeforeTPUDisable>
<showUniversalPushNotification>true</showUniversalPushNotification>
<getMessageHistoryRequestEnabled>true</getMessageHistoryRequestEnabled>
<nativePushProcessingEnabled>true</nativePushProcessingEnabled>
<webUrlInUniversalPushNotification>true</webUrlInUniversalPushNotification>
<cardNotificationWithSenderNameAndComment>true</cardNotificationWithSenderNameAndComment>
<routingFromTransactionPushToMessengerEnabled>true</routingFromTransactionPushToMessengerEnabled>
<pushLogoTypeUsing>true</pushLogoTypeUsing>
<UsePushAutoDisable>true</UsePushAutoDisable>
<reactivateMainPushNotifications>true</reactivateMainPushNotifications>
<hideMainPushNotificationsSwitcher>true</hideMainPushNotificationsSwitcher>
</node>
<node id="ift-node1-mp.testonline.sberbank.ru">
<buttonToPostLogin>true</buttonToPostLogin>
<pushHistoryAvailableInTabbarBank>true</pushHistoryAvailableInTabbarBank>
<MFMSMessageRequestType>2</MFMSMessageRequestType>
<NotificationSettingsOwn>true</NotificationSettingsOwn>
<autoTurnOffOperationPush>true</autoTurnOffOperationPush>
<TurnOffOperationPush>true</TurnOffOperationPush>
<MessagesWithExpired>true</MessagesWithExpired>
<showBestActionsInCuteCheque>true</showBestActionsInCuteCheque>
<showNotificationEntryPointTargetTapPrelogin>true</showNotificationEntryPointTargetTapPrelogin>
<showNotificationEntryPointTargetTapPostlogin>true</showNotificationEntryPointTargetTapPostlogin>
<newRejectAuthorizeAlert>true</newRejectAuthorizeAlert>
<showAlertBeforeTPUDisable>true</showAlertBeforeTPUDisable>
<showUniversalPushNotification>true</showUniversalPushNotification>
<getMessageHistoryRequestEnabled>true</getMessageHistoryRequestEnabled>
<nativePushProcessingEnabled>true</nativePushProcessingEnabled>
<webUrlInUniversalPushNotification>true</webUrlInUniversalPushNotification>
<cardNotificationWithSenderNameAndComment>true</cardNotificationWithSenderNameAndComment>
<routingFromTransactionPushToMessengerEnabled>true</routingFromTransactionPushToMessengerEnabled>
<pushLogoTypeUsing>true</pushLogoTypeUsing>
<UsePushAutoDisable>true</UsePushAutoDisable>
<reactivateMainPushNotifications>true</reactivateMainPushNotifications>
<hideMainPushNotificationsSwitcher>true</hideMainPushNotificationsSwitcher>
<PUSHNotificationsTransactionContentExtension>true</PUSHNotificationsTransactionContentExtension>
</node>
<node id="ift-node2-mp.testonline.sberbank.ru">
<buttonToPostLogin>true</buttonToPostLogin>
<pushHistoryAvailableInTabbarBank>true</pushHistoryAvailableInTabbarBank>
<MFMSMessageRequestType>2</MFMSMessageRequestType>
<NotificationSettingsOwn>true</NotificationSettingsOwn>
<autoTurnOffOperationPush>true</autoTurnOffOperationPush>
<TurnOffOperationPush>true</TurnOffOperationPush>
<MessagesWithExpired>true</MessagesWithExpired>
<showBestActionsInCuteCheque>true</showBestActionsInCuteCheque>
<showNotificationEntryPointTargetTapPrelogin>true</showNotificationEntryPointTargetTapPrelogin>
<showNotificationEntryPointTargetTapPostlogin>true</showNotificationEntryPointTargetTapPostlogin>
<newRejectAuthorizeAlert>true</newRejectAuthorizeAlert>
<showAlertBeforeTPUDisable>true</showAlertBeforeTPUDisable>
<showUniversalPushNotification>true</showUniversalPushNotification>
<getMessageHistoryRequestEnabled>true</getMessageHistoryRequestEnabled>
<nativePushProcessingEnabled>true</nativePushProcessingEnabled>
<webUrlInUniversalPushNotification>true</webUrlInUniversalPushNotification>
<cardNotificationWithSenderNameAndComment>true</cardNotificationWithSenderNameAndComment>
<routingFromTransactionPushToMessengerEnabled>true</routingFromTransactionPushToMessengerEnabled>
<pushLogoTypeUsing>true</pushLogoTypeUsing>
<UsePushAutoDisable>true</UsePushAutoDisable>
<reactivateMainPushNotifications>true</reactivateMainPushNotifications>
<hideMainPushNotificationsSwitcher>true</hideMainPushNotificationsSwitcher>
</node>
</nodes>
<bestActions>
<actions>
<bestActions name="Перевод клиенту Сбербанка" link="sberbankonline://payments/p2p-by-card-number"/>
<bestActions name="ЖКХ и домашний телефон" link="sberbankonline://payments/jkh"/>
<bestActions name="Мобильная связь" link="sberbankonline://payments/mobile-phone"/>
</actions>
<actions96>
<bestActions name="Перевод клиенту Сбербанка" link="sberbankonline://payments/p2p-by-phone-number"/>
<bestActions name="ЖКХ и домашний телефон" link="sberbankonline://payments/jkh"/>
<bestActions name="Мобильная связь" link="sberbankonline://payments/mobile-phone"/>
</actions96>
<operationAmount>1000</operationAmount>
</bestActions>
</param>
<param name="MAppNewBlockCardProcess" description="Обновленный процесс блокировки карт">
<type>service</type>
<enabled>true</enabled>
<nodes>
<node id="node0.online.sberbank.ru">
<enabled>true</enabled>
</node>
<node id="node1.online.sberbank.ru">
<enabled>true</enabled>
</node>
<node id="node2.online.sberbank.ru">
<enabled>true</enabled>
</node>
<node id="node3.online.sberbank.ru">
<enabled>true</enabled>
</node>
<node id="greenfield1.online.sberbank.ru">
<enabled>true</enabled>
</node>
<node id="mobile.sberbank.ru">
<enabled>true</enabled>
</node>
<node id="ift-node1.testonline.sberbank.ru">
<enabled>true</enabled>
</node>
<node id="ift-node2.testonline.sberbank.ru">
<enabled>true</enabled>
</node>
<node id="ift-node1-mp.testonline.sberbank.ru">
<enabled>true</enabled>
</node>
<node id="ift-node2-mp.testonline.sberbank.ru">
<enabled>true</enabled>
</node>
<node id="psinode2.testonline.sberbank.ru">
<enabled>true</enabled>
</node>
<node id="psinode1.testonline.sberbank.ru">
<enabled>true</enabled>
</node>
<node id="194.186.207.23">
<enabled>true</enabled>
</node>
</nodes>
</param>
<param name="PlasticCardLifeCycleMessages" description="Информационные сообщения по жизненному циклу карт">
<type>service</type>
<enabled>true</enabled>
<nodes>
<node id="greenfield1.online.sberbank.ru">
<enabled>false</enabled>
</node>
<node id="greenfield2.online.sberbank.ru">
<enabled>false</enabled>
</node>
<node id="mobile.sberbank.ru">
<enabled>false</enabled>
</node>
<node id="ift-node1.testonline.sberbank.ru">
<enabled>false</enabled>
</node>
<node id="ift-node2.testonline.sberbank.ru">
<enabled>false</enabled>
</node>
<node id="ift-node1-mp.testonline.sberbank.ru">
<enabled>false</enabled>
</node>
<node id="ift-node2-mp.testonline.sberbank.ru">
<enabled>false</enabled>
</node>
<node id="psinode2.testonline.sberbank.ru">
<enabled>false</enabled>
</node>
<node id="psinode1.testonline.sberbank.ru">
<enabled>false</enabled>
</node>
<node id="194.186.207.23">
<enabled>false</enabled>
</node>
</nodes>
</param>
<param name="PlasticCardLifeCycleMessagesV2" description="Информационные сообщения по жизненному циклу карт">
<type>service</type>
<enabled>true</enabled>
<nodes>
<node id="node0.online.sberbank.ru">
<enabled>true</enabled>
</node>
<node id="node1.online.sberbank.ru">
<enabled>true</enabled>
</node>
<node id="node2.online.sberbank.ru">
<enabled>true</enabled>
</node>
<node id="node3.online.sberbank.ru">
<enabled>true</enabled>
</node>
<node id="greenfield1.online.sberbank.ru">
<enabled>true</enabled>
</node>
<node id="greenfield2.online.sberbank.ru">
<enabled>true</enabled>
</node>
<node id="mobile.sberbank.ru">
<enabled>true</enabled>
</node>
<node id="ift-node1.testonline.sberbank.ru">
<enabled>true</enabled>
</node>
<node id="ift-node2.testonline.sberbank.ru">
<enabled>true</enabled>
</node>
<node id="ift-node1-mp.testonline.sberbank.ru">
<enabled>true</enabled>
</node>
<node id="ift-node2-mp.testonline.sberbank.ru">
<enabled>true</enabled>
</node>
<node id="psinode2.testonline.sberbank.ru">
<enabled>true</enabled>
</node>
<node id="psinode1.testonline.sberbank.ru">
<enabled>true</enabled>
</node>
<node id="194.186.207.23">
<enabled>true</enabled>
</node>
</nodes>
</param>
<param name="PlasticCardLifeCycleDetailMessages" description="Информационные сообщения по жизненному циклу карт внутри">
<type>service</type>
<enabled>true</enabled>
<nodes>
<node id="greenfield1.online.sberbank.ru">
<enabled>true</enabled>
</node>
<node id="greenfield2.online.sberbank.ru">
<enabled>true</enabled>
</node>
<node id="mobile.sberbank.ru">
<enabled>false</enabled>
</node>
<node id="ift-node1.testonline.sberbank.ru">
<enabled>false</enabled>
</node>
<node id="ift-node2.testonline.sberbank.ru">
<enabled>true</enabled>
</node>
<node id="ift-node1-mp.testonline.sberbank.ru">
<enabled>false</enabled>
</node>
<node id="ift-node2-mp.testonline.sberbank.ru">
<enabled>true</enabled>
</node>
<node id="psinode2.testonline.sberbank.ru">
<enabled>true</enabled>
</node>
<node id="psinode1.testonline.sberbank.ru">
<enabled>false</enabled>
</node>
<node id="194.186.207.23">
<enabled>true</enabled>
</node>
</nodes>
</param>
<param name="PlasticCardLifeCycleOtherCardsMessages" description="Информационные сообщения по жизненному циклу карт внутри 2">
<type>service</type>
<enabled>true</enabled>
<nodes>
<node id="greenfield1.online.sberbank.ru">
<enabled>true</enabled>
</node>
<node id="greenfield2.online.sberbank.ru">
<enabled>true</enabled>
</node>
<node id="mobile.sberbank.ru">
<enabled>false</enabled>
</node>
<node id="ift-node1.testonline.sberbank.ru">
<enabled>false</enabled>
</node>
<node id="ift-node2.testonline.sberbank.ru">
<enabled>true</enabled>
</node>
<node id="ift-node1-mp.testonline.sberbank.ru">
<enabled>false</enabled>
</node>
<node id="ift-node2-mp.testonline.sberbank.ru">
<enabled>true</enabled>
</node>
<node id="psinode2.testonline.sberbank.ru">
<enabled>true</enabled>
</node>
<node id="psinode1.testonline.sberbank.ru">
<enabled>false</enabled>
</node>
<node id="194.186.207.23">
<enabled>true</enabled>
</node>
</nodes>
</param>
<param name="LegacyCardInfoDoRequest" description="Старый способ запроса информации по КК">
<type>service</type>
<enabled>true</enabled>
<nodes>
<node id="greenfield1.online.sberbank.ru">
<enabled>true</enabled>
</node>
<node id="greenfield2.online.sberbank.ru">
<enabled>true</enabled>
</node>
<node id="mobile.sberbank.ru">
<enabled>true</enabled>
</node>
<node id="ift-node1.testonline.sberbank.ru">
<enabled>true</enabled>
</node>
<node id="ift-node2.testonline.sberbank.ru">
<enabled>true</enabled>
</node>
<node id="ift-node1-mp.testonline.sberbank.ru">
<enabled>true</enabled>
</node>
<node id="ift-node2-mp.testonline.sberbank.ru">
<enabled>true</enabled>
</node>
<node id="psinode2.testonline.sberbank.ru">
<enabled>true</enabled>
</node>
<node id="psinode1.testonline.sberbank.ru">
<enabled>true</enabled>
</node>
<node id="194.186.207.23">
<enabled>true</enabled>
</node>
</nodes>
</param>
<param name="MomentumCardEndDateMessage" description="Окончание срока действия карты Моментум">
<type>service</type>
<enabled>true</enabled>
<nodes>
<node id="greenfield1.online.sberbank.ru">
<enabled>true</enabled>
</node>
<node id="greenfield2.online.sberbank.ru">
<enabled>true</enabled>
</node>
<node id="mobile.sberbank.ru">
<enabled>true</enabled>
</node>
<node id="ift-node1.testonline.sberbank.ru">
<enabled>true</enabled>
</node>
<node id="ift-node2.testonline.sberbank.ru">
<enabled>true</enabled>
</node>
<node id="ift-node1-mp.testonline.sberbank.ru">
<enabled>true</enabled>
</node>
<node id="ift-node2-mp.testonline.sberbank.ru">
<enabled>true</enabled>
</node>
<node id="psinode2.testonline.sberbank.ru">
<enabled>true</enabled>
</node>
<node id="psinode1.testonline.sberbank.ru">
<enabled>true</enabled>
</node>
<node id="194.186.207.23">
<enabled>true</enabled>
</node>
</nodes>
</param>
<param name="MomentumCardEndDateMessageV2" description="Окончание срока действия карты Моментум НОВЫЙ, начиная с 9.6">
<type>service</type>
<enabled>true</enabled>
<nodes>
<node id="greenfield1.online.sberbank.ru">
<enabled>true</enabled>
</node>
<node id="greenfield2.online.sberbank.ru">
<enabled>true</enabled>
</node>
<node id="mobile.sberbank.ru">
<enabled>true</enabled>
</node>
<node id="ift-node1.testonline.sberbank.ru">
<enabled>true</enabled>
</node>
<node id="ift-node2.testonline.sberbank.ru">
<enabled>true</enabled>
</node>
<node id="ift-node1-mp.testonline.sberbank.ru">
<enabled>true</enabled>
</node>
<node id="ift-node2-mp.testonline.sberbank.ru">
<enabled>true</enabled>
</node>
<node id="psinode2.testonline.sberbank.ru">
<enabled>true</enabled>
</node>
<node id="psinode1.testonline.sberbank.ru">
<enabled>true</enabled>
</node>
<node id="194.186.207.23">
<enabled>true</enabled>
</node>
</nodes>
</param>
<param name="CurrencyCardBankDetail" description="Валютные реквизиты карты">
<type>service</type>
<enabled>true</enabled>
<nodes>
<node id="ift-node1-mp.testonline.sberbank.ru">
<enabled>true</enabled>
</node>
<node id="ift-node1.testonline.sberbank.ru">
<enabled>true</enabled>
</node>
</nodes>
<usdbanksdetail swift="IRVTUS3N" receivername="The Bank of New York Mellon, New York"/>
<eurobanksdetail swift="DEUTDEFF" receivername="DEUTSCHE BANK AG, Frankfurt am Main"/>
</param>
<param name="EribStatePaymentShortCuts" description="Каталог бюджетных платежей - быстрый доступ к популярным услугам">
<type>list</type>
<shortcuts>
<shortcut>
<title>Штрафы ГИБДД</title>
<icon>
https://stat.online.sberbank.ru/PhizIC-res/logos/PU/7707089101.jpg
</icon>
<nodes>
<node id="ift-node1-mp.testonline.sberbank.ru">
<catalogID>624234</catalogID>
</node>
<node id="ift-node2-mp.testonline.sberbank.ru">
<catalogID>623567</catalogID>
</node>
<node id="ift-node1.testonline.sberbank.ru">
<catalogID>624234</catalogID>
</node>
<node id="ift-node2.testonline.sberbank.ru">
<catalogID>623567</catalogID>
</node>
</nodes>
</shortcut>
<shortcut>
<title>Налоги</title>
<icon>
https://stat.online.sberbank.ru/PhizIC-res/IMG/PU/20/63/61/2b26d928c6b985710071f62251_38347.jpg
</icon>
<nodes>
<node id="ift-node1-mp.testonline.sberbank.ru">
<catalogID>617638</catalogID>
</node>
<node id="ift-node2-mp.testonline.sberbank.ru">
<catalogID>615397</catalogID>
</node>
<node id="ift-node1.testonline.sberbank.ru">
<catalogID>617638</catalogID>
</node>
<node id="ift-node2.testonline.sberbank.ru">
<catalogID>615397</catalogID>
</node>
</nodes>
</shortcut>
</shortcuts>
</param>
<param name="MobileBankSettings" description="Настройки для подключения МБ в МП">
<type>list</type>
<MobileBankColdPeriodDuration>7 дней</MobileBankColdPeriodDuration>
<nodes>
<node id="greenfield0.online.sberbank.ru">
<mobileBankFromSetting>true</mobileBankFromSetting>
<mobileBankFromCardSetting>true</mobileBankFromCardSetting>
<CardPhoneListCacheEnabled>true</CardPhoneListCacheEnabled>
<mobileBankChangePhone>true</mobileBankChangePhone>
<FullTariffTurnOffEnabled>true</FullTariffTurnOffEnabled>
<ShowNotificationTerm>true</ShowNotificationTerm>
</node>
<node id="greenfield1.online.sberbank.ru">
<mobileBankFromSetting>true</mobileBankFromSetting>
<mobileBankFromCardSetting>true</mobileBankFromCardSetting>
<CardPhoneListCacheEnabled>true</CardPhoneListCacheEnabled>
<mobileBankChangePhone>true</mobileBankChangePhone>
<FullTariffTurnOffEnabled>true</FullTariffTurnOffEnabled>
<ShowNotificationTerm>true</ShowNotificationTerm>
</node>
<node id="psinode1.testonline.sberbank.ru">
<mobileBankFromSetting>true</mobileBankFromSetting>
<mobileBankFromCardSetting>true</mobileBankFromCardSetting>
<CardPhoneListCacheEnabled>true</CardPhoneListCacheEnabled>
<mobileBankChangePhone>true</mobileBankChangePhone>
<FullTariffTurnOffEnabled>true</FullTariffTurnOffEnabled>
<ShowNotificationTerm>true</ShowNotificationTerm>
</node>
<node id="mobile.sberbank.ru">
<mobileBankFromSetting>true</mobileBankFromSetting>
<mobileBankFromCardSetting>true</mobileBankFromCardSetting>
<CardPhoneListCacheEnabled>true</CardPhoneListCacheEnabled>
<mobileBankChangePhone>true</mobileBankChangePhone>
<FullTariffTurnOffEnabled>true</FullTariffTurnOffEnabled>
<ShowNotificationTerm>true</ShowNotificationTerm>
</node>
<node id="194.186.207.23">
<mobileBankFromSetting>true</mobileBankFromSetting>
<mobileBankFromCardSetting>true</mobileBankFromCardSetting>
<CardPhoneListCacheEnabled>true</CardPhoneListCacheEnabled>
<mobileBankChangePhone>true</mobileBankChangePhone>
<FullTariffTurnOffEnabled>true</FullTariffTurnOffEnabled>
<ShowNotificationTerm>true</ShowNotificationTerm>
</node>
<node id="ift-node1.testonline.sberbank.ru">
<mobileBankFromSetting>true</mobileBankFromSetting>
<mobileBankFromCardSetting>true</mobileBankFromCardSetting>
<CardPhoneListCacheEnabled>true</CardPhoneListCacheEnabled>
<mobileBankChangePhone>true</mobileBankChangePhone>
<FullTariffTurnOffEnabled>true</FullTariffTurnOffEnabled>
<ShowNotificationTerm>true</ShowNotificationTerm>
</node>
<node id="ift-node2.testonline.sberbank.ru">
<mobileBankFromSetting>true</mobileBankFromSetting>
<mobileBankFromCardSetting>true</mobileBankFromCardSetting>
<CardPhoneListCacheEnabled>true</CardPhoneListCacheEnabled>
<mobileBankChangePhone>true</mobileBankChangePhone>
<FullTariffTurnOffEnabled>true</FullTariffTurnOffEnabled>
<ShowNotificationTerm>true</ShowNotificationTerm>
</node>
<node id="ift-node1-mp.testonline.sberbank.ru">
<mobileBankFromSetting>true</mobileBankFromSetting>
<mobileBankFromCardSetting>true</mobileBankFromCardSetting>
<CardPhoneListCacheEnabled>true</CardPhoneListCacheEnabled>
<mobileBankChangePhone>true</mobileBankChangePhone>
<FullTariffTurnOffEnabled>true</FullTariffTurnOffEnabled>
<ShowNotificationTerm>true</ShowNotificationTerm>
</node>
<node id="ift-node2-mp.testonline.sberbank.ru">
<mobileBankFromSetting>true</mobileBankFromSetting>
<mobileBankFromCardSetting>true</mobileBankFromCardSetting>
<CardPhoneListCacheEnabled>true</CardPhoneListCacheEnabled>
<mobileBankChangePhone>true</mobileBankChangePhone>
<FullTariffTurnOffEnabled>true</FullTariffTurnOffEnabled>
<ShowNotificationTerm>true</ShowNotificationTerm>
</node>
</nodes>
</param>
<param name="a2aoverseastransferwutohide" description="Перевод денежных средств за границу через Western Union">
<type>list</type>
<enabled>true</enabled>
<AgreementLink>
https://test.stat.online.sberbank.ru/WESTERNUNION/Oferta_Western_Union_a2a.pdf
</AgreementLink>
<WUViewTutorial description="Отображение туториала">
<enabled>true</enabled>
<countTutorial>1</countTutorial>
</WUViewTutorial>
<nodes>
<node id="node0.online.sberbank.ru">
<enabled>false</enabled>
<INNWU>7727067410</INNWU>
</node>
<node id="node1.online.sberbank.ru">
<enabled>false</enabled>
<INNWU>7727067410</INNWU>
</node>
<node id="node2.online.sberbank.ru">
<enabled>false</enabled>
<INNWU>7727067410</INNWU>
</node>
<node id="node3.online.sberbank.ru">
<enabled>false</enabled>
<INNWU>7727067410</INNWU>
</node>
<node id="greenfield1.online.sberbank.ru">
<enabled>false</enabled>
<INNWU>7727067410</INNWU>
</node>
<node id="greenfield2.online.sberbank.ru">
<enabled>false</enabled>
<INNWU>7727067410</INNWU>
</node>
<node id="194.186.207.23">
<enabled>true</enabled>
<INNWU>7727067410</INNWU>
</node>
<node id="mobile.sberbank.ru">
<enabled>true</enabled>
<INNWU>7727067410</INNWU>
</node>
<node id="ift-node0.testonline.sberbank.ru">
<enabled>true</enabled>
<INNWU>7727067410</INNWU>
</node>
<node id="ift-node1.testonline.sberbank.ru">
<enabled>true</enabled>
<INNWU>7727067410</INNWU>
</node>
<node id="ift-node2.testonline.sberbank.ru">
<enabled>true</enabled>
<INNWU>7727067410</INNWU>
</node>
<node id="ift-node0-mp.testonline.sberbank.ru">
<enabled>true</enabled>
<INNWU>7727067410</INNWU>
</node>
<node id="ift-node1-mp.testonline.sberbank.ru">
<enabled>true</enabled>
<INNWU>7727067410</INNWU>
</node>
<node id="ift-node2-mp.testonline.sberbank.ru">
<enabled>true</enabled>
<INNWU>7727067410</INNWU>
</node>
<node id="10.21.152.7">
<enabled>true</enabled>
<INNWU>7727067410</INNWU>
</node>
</nodes>
</param>
<param name="EribNewGibddCatalog" description="Новый каталог Госуслуги, Налоги, Штрафы, Пошлины на замену старого">
<type>list</type>
<nodes>
<node id="ift-node1-mp.testonline.sberbank.ru">
<enabled>true</enabled>
<catalogID>1526</catalogID>
</node>
<node id="ift-node2-mp.testonline.sberbank.ru">
<enabled>true</enabled>
<catalogID>2428</catalogID>
</node>
<node id="ift-node1.testonline.sberbank.ru">
<enabled>true</enabled>
<catalogID>1526</catalogID>
</node>
<node id="ift-node2.testonline.sberbank.ru">
<enabled>true</enabled>
<catalogID>2428</catalogID>
</node>
</nodes>
</param>
<param name="PaymentsAndTransfers">
<type>list</type>
<nodes>
<node id="greenfield1.online.sberbank.ru">
<smartSearchFromPayment>true</smartSearchFromPayment>
<BarcodeTutorialEnabled>true</BarcodeTutorialEnabled>
<BarcodeScanIconEnabled>true</BarcodeScanIconEnabled>
<QRCodeBubbleEnabled>false</QRCodeBubbleEnabled>
</node>
<node id="greenfield2.online.sberbank.ru">
<smartSearchFromPayment>true</smartSearchFromPayment>
<BarcodeTutorialEnabled>true</BarcodeTutorialEnabled>
<BarcodeScanIconEnabled>true</BarcodeScanIconEnabled>
<QRCodeBubbleEnabled>true</QRCodeBubbleEnabled>
</node>
<node id="node1.online.sberbank.ru">
<smartSearchFromPayment>true</smartSearchFromPayment>
<BarcodeTutorialEnabled>true</BarcodeTutorialEnabled>
<BarcodeScanIconEnabled>true</BarcodeScanIconEnabled>
<QRCodeBubbleEnabled>true</QRCodeBubbleEnabled>
</node>
<node id="node2.online.sberbank.ru">
<smartSearchFromPayment>true</smartSearchFromPayment>
<BarcodeTutorialEnabled>true</BarcodeTutorialEnabled>
<BarcodeScanIconEnabled>true</BarcodeScanIconEnabled>
<QRCodeBubbleEnabled>true</QRCodeBubbleEnabled>
</node>
<node id="node3.online.sberbank.ru">
<smartSearchFromPayment>true</smartSearchFromPayment>
<BarcodeTutorialEnabled>true</BarcodeTutorialEnabled>
<BarcodeScanIconEnabled>true</BarcodeScanIconEnabled>
<QRCodeBubbleEnabled>true</QRCodeBubbleEnabled>
</node>
<node id="node4.online.sberbank.ru">
<smartSearchFromPayment>true</smartSearchFromPayment>
<BarcodeTutorialEnabled>true</BarcodeTutorialEnabled>
<BarcodeScanIconEnabled>true</BarcodeScanIconEnabled>
<QRCodeBubbleEnabled>true</QRCodeBubbleEnabled>
</node>
<node id="mobile.sberbank.ru">
<smartSearchFromPayment>true</smartSearchFromPayment>
<BarcodeTutorialEnabled>true</BarcodeTutorialEnabled>
<BarcodeScanIconEnabled>true</BarcodeScanIconEnabled>
<QRCodeBubbleEnabled>true</QRCodeBubbleEnabled>
</node>
<node id="ift-node1.testonline.sberbank.ru">
<smartSearchFromPayment>true</smartSearchFromPayment>
<BarcodeTutorialEnabled>false</BarcodeTutorialEnabled>
<BarcodeScanIconEnabled>true</BarcodeScanIconEnabled>
<QRCodeBubbleEnabled>true</QRCodeBubbleEnabled>
</node>
<node id="ift-node2.testonline.sberbank.ru">
<smartSearchFromPayment>true</smartSearchFromPayment>
<BarcodeTutorialEnabled>false</BarcodeTutorialEnabled>
<BarcodeScanIconEnabled>true</BarcodeScanIconEnabled>
<QRCodeBubbleEnabled>true</QRCodeBubbleEnabled>
</node>
<node id="ift-node1-mp.testonline.sberbank.ru">
<smartSearchFromPayment>true</smartSearchFromPayment>
<BarcodeTutorialEnabled>false</BarcodeTutorialEnabled>
<BarcodeScanIconEnabled>true</BarcodeScanIconEnabled>
<QRCodeBubbleEnabled>true</QRCodeBubbleEnabled>
</node>
<node id="ift-node2-mp.testonline.sberbank.ru">
<smartSearchFromPayment>true</smartSearchFromPayment>
<BarcodeTutorialEnabled>false</BarcodeTutorialEnabled>
<BarcodeScanIconEnabled>true</BarcodeScanIconEnabled>
<QRCodeBubbleEnabled>true</QRCodeBubbleEnabled>
</node>
<node id="psinode2.testonline.sberbank.ru">
<smartSearchFromPayment>true</smartSearchFromPayment>
<BarcodeTutorialEnabled>true</BarcodeTutorialEnabled>
<BarcodeScanIconEnabled>true</BarcodeScanIconEnabled>
<QRCodeBubbleEnabled>true</QRCodeBubbleEnabled>
</node>
<node id="psinode1.testonline.sberbank.ru">
<smartSearchFromPayment>true</smartSearchFromPayment>
<BarcodeTutorialEnabled>true</BarcodeTutorialEnabled>
<BarcodeScanIconEnabled>true</BarcodeScanIconEnabled>
<QRCodeBubbleEnabled>true</QRCodeBubbleEnabled>
</node>
<node id="194.186.207.23">
<smartSearchFromPayment>true</smartSearchFromPayment>
<BarcodeTutorialEnabled>true</BarcodeTutorialEnabled>
<BarcodeScanIconEnabled>true</BarcodeScanIconEnabled>
<QRCodeBubbleEnabled>true</QRCodeBubbleEnabled>
</node>
</nodes>
</param>
<param name="VIPClientIncreaseLimitClaim" description="Увеличение индивидуального лимита для ВИП клиентов">
<type>service</type>
<increaseLimitEnabled>true</increaseLimitEnabled>
<nodes>
<node id="node0.online.sberbank.ru">
<enabled>true</enabled>
<increaseLimitEnabled>true</increaseLimitEnabled>
</node>
<node id="node1.online.sberbank.ru">
<enabled>true</enabled>
<increaseLimitEnabled>true</increaseLimitEnabled>
</node>
<node id="node2.online.sberbank.ru">
<enabled>true</enabled>
<increaseLimitEnabled>true</increaseLimitEnabled>
</node>
<node id="node3.online.sberbank.ru">
<enabled>true</enabled>
<increaseLimitEnabled>true</increaseLimitEnabled>
</node>
<node id="greenfield1.online.sberbank.ru">
<enabled>true</enabled>
<increaseLimitEnabled>true</increaseLimitEnabled>
</node>
<node id="ift-node1.testonline.sberbank.ru">
<enabled>true</enabled>
<increaseLimitEnabled>true</increaseLimitEnabled>
</node>
<node id="ift-node2.testonline.sberbank.ru">
<enabled>true</enabled>
<increaseLimitEnabled>true</increaseLimitEnabled>
</node>
<node id="ift-node1-mp.testonline.sberbank.ru">
<enabled>true</enabled>
<increaseLimitEnabled>true</increaseLimitEnabled>
</node>
<node id="ift-node2-mp.testonline.sberbank.ru">
<enabled>true</enabled>
<increaseLimitEnabled>true</increaseLimitEnabled>
</node>
<node id="ift-node4-mp.testonline.sberbank.ru">
<enabled>true</enabled>
<increaseLimitEnabled>true</increaseLimitEnabled>
</node>
<node id="psinode2.testonline.sberbank.ru">
<enabled>true</enabled>
<increaseLimitEnabled>false</increaseLimitEnabled>
</node>
<node id="psinode1.testonline.sberbank.ru">
<enabled>true</enabled>
<increaseLimitEnabled>false</increaseLimitEnabled>
</node>
<node id="mobile.sberbank.ru">
<enabled>false</enabled>
<increaseLimitEnabled>false</increaseLimitEnabled>
</node>
</nodes>
</param>
<param name="MessengerBeruGiftcard" description="Сертификаты Беру в диалогах">
<type>list</type>
<sendVersions>
<version name="9.4.0">
<enabled>true</enabled>
</version>
<version name="9.5.0">
<enabled>true</enabled>
</version>
<version name="9.6.0">
<enabled>true</enabled>
</version>
<version name="9.7.0">
<enabled>true</enabled>
</version>
</sendVersions>
<receiveVersions>
<version name="9.4.0">
<enabled>true</enabled>
</version>
<version name="9.5.0">
<enabled>true</enabled>
</version>
<version name="9.6.0">
<enabled>true</enabled>
</version>
<version name="9.7.0">
<enabled>true</enabled>
</version>
</receiveVersions>
<agreements>
<textSender>
Приобретая подарочный сертификат, покупатель дает согласие ПАО Сбербанк на передачу своих персональных данных - ФИО и адреса электронной почты - маркетплейсу Беру (ООО "Яндекс Маркет")для оформления покупки подарочного сертификата.
</textSender>
</agreements>
<nodes>
<node id="node0.online.sberbank.ru">
<billingID>284</billingID>
<providerID>684391</providerID>
<serviceID>486042900175</serviceID>
</node>
<node id="node1.online.sberbank.ru">
<billingID>284</billingID>
<providerID>684391</providerID>
<serviceID>486042900175</serviceID>
</node>
<node id="node2.online.sberbank.ru">
<billingID>284</billingID>
<providerID>500501445</providerID>
<serviceID>486042900175</serviceID>
</node>
<node id="node3.online.sberbank.ru">
<billingID>284</billingID>
<providerID>500500795</providerID>
<serviceID>486042900175</serviceID>
</node>
<node id="node4.online.sberbank.ru">
<billingID>284</billingID>
<providerID>500495145</providerID>
<serviceID>486042900175</serviceID>
</node>
<node id="greenfield1.online.sberbank.ru">
<billingID>284</billingID>
<providerID>550533493</providerID>
<serviceID>486042900175</serviceID>
</node>
<node id="greenfield2.online.sberbank.ru">
<billingID>284</billingID>
<providerID>550533493</providerID>
<serviceID>486042900175</serviceID>
</node>
<node id="194.186.207.23">
<billingID>284</billingID>
<providerID>635832</providerID>
<serviceID>635832</serviceID>
</node>
<node id="ift-node1.testonline.sberbank.ru">
<billingID>344</billingID>
<providerID>623383</providerID>
<serviceID>623383</serviceID>
</node>
<node id="ift-node1-mp.testonline.sberbank.ru">
<billingID>344</billingID>
<providerID>623383</providerID>
<serviceID>623383</serviceID>
</node>
<node id="ift-node2-mp.testonline.sberbank.ru">
<billingID>344</billingID>
<providerID>623383</providerID>
<serviceID>623383</serviceID>
</node>
<node id="ift-node2.testonline.sberbank.ru">
<billingID>344</billingID>
<providerID>623383</providerID>
<serviceID>623383</serviceID>
</node>
<node id="mobile.sberbank.ru">
<billingID>344</billingID>
<providerID>688848</providerID>
<serviceID>688848</serviceID>
</node>
</nodes>
</param>
<param name="MessengerLitresGiftcard" description="Сертификаты ЛитРес в Диалогах">
<type>list</type>
<sendVersions>
<version name="9.4.0">
<enabled>true</enabled>
</version>
<version name="9.5.0">
<enabled>true</enabled>
</version>
<version name="9.6.0">
<enabled>true</enabled>
</version>
<version name="9.7.0">
<enabled>true</enabled>
</version>
</sendVersions>
<receiveVersions>
<version name="9.4.0">
<enabled>true</enabled>
</version>
<version name="9.5.0">
<enabled>true</enabled>
</version>
<version name="9.6.0">
<enabled>false</enabled>
</version>
<version name="9.7.0">
<enabled>true</enabled>
</version>
</receiveVersions>
<agreements>
<textSender>
Приобретая электронную книгу, покупатель дает согласие ПАО Сбербанк на передачу адреса электронной почты ООО "Препейд Солюшенс" для оформления покупки сертификата.
</textSender>
<textReceiver>
Я даю согласие ПАО Сбербанк на передачу номера мобильного телефона, используемого в мобильном приложении "Сбербанк Онлайн", ООО "ЛитРес" с целью авторизации или регистрации в личном кабинете онлайн-библиотеки ЛитРес.
</textReceiver>
</agreements>
<nodes>
<node id="node0.online.sberbank.ru">
<billingID>284</billingID>
<providerID>550538129</providerID>
<serviceID>550538129</serviceID>
<accountEribFieldName>S503789069614A503789059641</accountEribFieldName>
<textEribFieldName>S503789069614A503789062082</textEribFieldName>
<dateEribFieldName>S503789069614A503789062597</dateEribFieldName>
</node>
<node id="node1.online.sberbank.ru">
<billingID>284</billingID>
<providerID>550538129</providerID>
<serviceID>550538129</serviceID>
<accountEribFieldName>S503789069614A503789059641</accountEribFieldName>
<textEribFieldName>S503789069614A503789062082</textEribFieldName>
<dateEribFieldName>S503789069614A503789062597</dateEribFieldName>
</node>
<node id="node2.online.sberbank.ru">
<billingID>284</billingID>
<providerID>550538129</providerID>
<serviceID>550538129</serviceID>
<accountEribFieldName>S503789069614A503789059641</accountEribFieldName>
<textEribFieldName>S503789069614A503789062082</textEribFieldName>
<dateEribFieldName>S503789069614A503789062597</dateEribFieldName>
</node>
<node id="node3.online.sberbank.ru">
<billingID>284</billingID>
<providerID>550538129</providerID>
<serviceID>550538129</serviceID>
<accountEribFieldName>S503789069614A503789059641</accountEribFieldName>
<textEribFieldName>S503789069614A503789062082</textEribFieldName>
<dateEribFieldName>S503789069614A503789062597</dateEribFieldName>
</node>
<node id="node4.online.sberbank.ru">
<billingID>284</billingID>
<providerID>550538129</providerID>
<serviceID>550538129</serviceID>
<accountEribFieldName>S503789069614A503789059641</accountEribFieldName>
<textEribFieldName>S503789069614A503789062082</textEribFieldName>
<dateEribFieldName>S503789069614A503789062597</dateEribFieldName>
</node>
<node id="greenfield1.online.sberbank.ru">
<billingID>284</billingID>
<providerID>550538129</providerID>
<serviceID>550538129</serviceID>
<accountEribFieldName>S503789069614A503789059641</accountEribFieldName>
<textEribFieldName>S503789069614A503789062082</textEribFieldName>
<dateEribFieldName>S503789069614A503789062597</dateEribFieldName>
</node>
<node id="greenfield2.online.sberbank.ru">
<billingID>284</billingID>
<providerID>550538129</providerID>
<serviceID>550538129</serviceID>
<accountEribFieldName>S503789069614A503789059641</accountEribFieldName>
<textEribFieldName>S503789069614A503789062082</textEribFieldName>
<dateEribFieldName>S503789069614A503789062597</dateEribFieldName>
</node>
<node id="194.186.207.23">
<billingID>344</billingID>
<providerID>688927</providerID>
<serviceID>688927</serviceID>
<accountEribFieldName>S357407913386A357902514918</accountEribFieldName>
<textEribFieldName>S357407913386A357902514945</textEribFieldName>
<dateEribFieldName>S357407913386A357902514947</dateEribFieldName>
</node>
<node id="ift-node1.testonline.sberbank.ru">
<billingID>344</billingID>
<providerID>623567</providerID>
<serviceID>623567</serviceID>
<accountEribFieldName>S202108599547A190216781206</accountEribFieldName>
<textEribFieldName>S202108599547A190216781214</textEribFieldName>
<dateEribFieldName>S202108599547A190216781217</dateEribFieldName>
</node>
<node id="ift-node1-mp.testonline.sberbank.ru">
<billingID>344</billingID>
<providerID>623567</providerID>
<serviceID>623567</serviceID>
<accountEribFieldName>S202108599547A190216781206</accountEribFieldName>
<textEribFieldName>S202108599547A190216781214</textEribFieldName>
<dateEribFieldName>S202108599547A190216781217</dateEribFieldName>
</node>
<node id="ift-node2-mp.testonline.sberbank.ru">
<billingID>344</billingID>
<providerID>623567</providerID>
<serviceID>623567</serviceID>
<accountEribFieldName>S202108599547A190216781206</accountEribFieldName>
<textEribFieldName>S202108599547A190216781214</textEribFieldName>
<dateEribFieldName>S202108599547A190216781217</dateEribFieldName>
</node>
<node id="ift-node2.testonline.sberbank.ru">
<billingID>344</billingID>
<providerID>623567</providerID>
<serviceID>623567</serviceID>
<accountEribFieldName>S202108599547A190216781206</accountEribFieldName>
<textEribFieldName>S202108599547A190216781214</textEribFieldName>
<dateEribFieldName>S202108599547A190216781217</dateEribFieldName>
</node>
<node id="mobile.sberbank.ru">
<billingID>344</billingID>
<providerID>688927</providerID>
<serviceID>688927</serviceID>
<accountEribFieldName>S357407913386A357902514918</accountEribFieldName>
<textEribFieldName>S357407913386A357902514945</textEribFieldName>
<dateEribFieldName>S357407913386A357902514947</dateEribFieldName>
</node>
</nodes>
</param>
<param name="MessangerGiftsTab" description="Рубильник на таб Подарки в Диалогах">
<type>setting</type>
<enabled>true</enabled>
</param>
<param name="TelecomParameters" description="Телеком: Хост стенда, параметры доступа">
<type>list</type>
<nodes>
<node id="node0.online.sberbank.ru">
<TelecomHost>https://api.sberbank-tele.com/v2/</TelecomHost>
<TelecomWidgetLimitsTabEnabled>true</TelecomWidgetLimitsTabEnabled>
</node>
<node id="node1.online.sberbank.ru">
<TelecomHost>https://api.sberbank-tele.com/v2/</TelecomHost>
<TelecomWidgetLimitsTabEnabled>true</TelecomWidgetLimitsTabEnabled>
</node>
<node id="node2.online.sberbank.ru">
<TelecomHost>https://api.sberbank-tele.com/v2/</TelecomHost>
<TelecomWidgetLimitsTabEnabled>true</TelecomWidgetLimitsTabEnabled>
</node>
<node id="node3.online.sberbank.ru">
<TelecomHost>https://api.sberbank-tele.com/v2/</TelecomHost>
<TelecomWidgetLimitsTabEnabled>true</TelecomWidgetLimitsTabEnabled>
</node>
<node id="node4.online.sberbank.ru">
<TelecomHost>https://api.sberbank-tele.com/v2/</TelecomHost>
<TelecomWidgetLimitsTabEnabled>true</TelecomWidgetLimitsTabEnabled>
</node>
<node id="greenfield1.online.sberbank.ru">
<TelecomHost>https://api.sberbank-tele.com/v2/</TelecomHost>
<TelecomWidgetLimitsTabEnabled>true</TelecomWidgetLimitsTabEnabled>
</node>
<node id="greenfield2.online.sberbank.ru">
<TelecomHost>https://api.sberbank-tele.com/v2/</TelecomHost>
<TelecomWidgetLimitsTabEnabled>true</TelecomWidgetLimitsTabEnabled>
</node>
<node id="psinode2.testonline.sberbank.ru">
<TelecomHost>https://api-test.sberbank-tele.com/v2/</TelecomHost>
<TelecomWidgetLimitsTabEnabled>true</TelecomWidgetLimitsTabEnabled>
</node>
<node id="psinode1.testonline.sberbank.ru">
<TelecomHost>https://api-test.sberbank-tele.com/v2/</TelecomHost>
<TelecomWidgetLimitsTabEnabled>true</TelecomWidgetLimitsTabEnabled>
</node>
<node id="194.186.207.23">
<TelecomHost>https://api-test.sberbank-tele.com/v2/</TelecomHost>
<TelecomWidgetLimitsTabEnabled>true</TelecomWidgetLimitsTabEnabled>
</node>
<node id="ift-node1.testonline.sberbank.ru">
<TelecomHost>https://api-test.sberbank-tele.com/v2/</TelecomHost>
<TelecomWidgetLimitsTabEnabled>true</TelecomWidgetLimitsTabEnabled>
</node>
<node id="ift-node1-mp.testonline.sberbank.ru">
<TelecomHost>https://api-test.sberbank-tele.com/v2/</TelecomHost>
<TelecomWidgetLimitsTabEnabled>true</TelecomWidgetLimitsTabEnabled>
</node>
<node id="ift-node2-mp.testonline.sberbank.ru">
<TelecomHost>https://api-test.sberbank-tele.com/v2/</TelecomHost>
<TelecomWidgetLimitsTabEnabled>true</TelecomWidgetLimitsTabEnabled>
</node>
<node id="ift-node2.testonline.sberbank.ru">
<TelecomHost>https://api-test.sberbank-tele.com/v2/</TelecomHost>
<TelecomWidgetLimitsTabEnabled>true</TelecomWidgetLimitsTabEnabled>
</node>
<node id="mobile.sberbank.ru">
<TelecomHost>https://api-test.sberbank-tele.com/v2/</TelecomHost>
<TelecomWidgetLimitsTabEnabled>true</TelecomWidgetLimitsTabEnabled>
</node>
</nodes>
</param>
<param name="showTariffsLink" description="Пункт меню Тарифы, Лимиты и Сроки">
<type>setting</type>
<enabled>true</enabled>
<link>
https://stat.online.sberbank.ru/PhizIC-res/mapicfg/tariffs.xml
</link>
<warningTextEnabled>true</warningTextEnabled>
<warningText>
Для операций в Сбербанке Онлайн. Полный перечень тарифов, лимитов и сроков осуществления переводов и платежей вы можете найти на сайте [www.sberbank.ru](https://www.sberbank.ru).
</warningText>
<nodes>
<node id="node0.online.sberbank.ru">
<enabled>true</enabled>
</node>
<node id="node1.online.sberbank.ru">
<enabled>true</enabled>
</node>
<node id="node2.online.sberbank.ru">
<enabled>true</enabled>
</node>
<node id="node3.online.sberbank.ru">
<enabled>true</enabled>
</node>
<node id="node4.online.sberbank.ru">
<enabled>true</enabled>
</node>
<node id="greenfield1.online.sberbank.ru">
<enabled>true</enabled>
</node>
<node id="greenfield2.online.sberbank.ru">
<enabled>true</enabled>
</node>
<node id="ift-node1-mp.testonline.sberbank.ru" description="Стенд ИФТ блок 1 (мобильный)">
<enabled>true</enabled>
</node>
<node id="mobile.sberbank.ru" description="Стенд ПСИ">
<enabled>true</enabled>
</node>
</nodes>
</param>
<param name="interTransfer" description="Перевод для получения наличных в Western Union">
<type>list</type>
<enabled>true</enabled>
<serviceProviders>
<serviceProvider name="Western Union" visibleName="Western Union">
<nodes>
<node id="ift-node1-mp.testonline.sberbank.ru">
<targetBilling>344</targetBilling>
<targetProvider>623561</targetProvider>
<targetService>623561</targetService>
</node>
<node id="mobile.sberbank.ru">
<targetBilling>344</targetBilling>
<targetProvider>688869</targetProvider>
<targetService>688869</targetService>
</node>
</nodes>
</serviceProvider>
</serviceProviders>
<!--
Параметр showTutorial отвечает за доступность экрана Промо при входе в приложение
-->
<showTutorial>true</showTutorial>
<!--
Параметр WUTutorial отвечает за доступность и количество показов экрана Туториал при входе в операцию
-->
<WUTutorial description="Количество отображений Туториала">
<enabled>true</enabled>
<countTutorial>5</countTutorial>
</WUTutorial>
<links>
<link name="additional">https://www.sberbank.ru/ru/person/remittance</link>
<link name="offer">
https://test.stat.online.sberbank.ru/WESTERNUNION/oferta_western_union.pdf
</link>
</links>
<isShortFraudScreen>true</isShortFraudScreen>
<isLongFraudScreen>false</isLongFraudScreen>
</param>
<param name="SelfEmployedV2" description="Сервис самозанятые">
<type>service</type>
<enabled>true</enabled>
<assignService>true</assignService>
<unassignService>true</unassignService>
<incomesListService>true</incomesListService>
<deleteIncomeService>true</deleteIncomeService>
<addIncomeService>true</addIncomeService>
</param>
<param name="PersonalizationDDP" description="Персонализация от сервиса умного поиска">
<type>setting</type>
<enabled>true</enabled>
</param>
<param name="authBlockingScreen" description="Выводить клиенту врем, через которое будет доступен вход в МП, после блокировки 5-значного пароля">
<type>setting</type>
<enabled>true</enabled>
</param>
<param name="NotificationsEnableSuggestion" description="">
<type>setting</type>
<enabled>true</enabled>
<periodInDays>1</periodInDays>
</param>
<param name="CreditCardInTransfersPermission" description="Управление запретом на использование кредитных карт в переводах p2p">
<type>setting</type>
<enabled>true</enabled>
<nodes>
<node id="node0.online.sberbank.ru">
<enabled>true</enabled>
</node>
<node id="node1.online.sberbank.ru">
<enabled>true</enabled>
</node>
<node id="node2.online.sberbank.ru">
<enabled>true</enabled>
</node>
<node id="node3.online.sberbank.ru">
<enabled>true</enabled>
</node>
<node id="node4.online.sberbank.ru">
<enabled>true</enabled>
</node>
<node id="greenfield1.online.sberbank.ru">
<enabled>true</enabled>
</node>
<node id="greenfield2.online.sberbank.ru">
<enabled>true</enabled>
</node>
<node id="ift-node1-mp.testonline.sberbank.ru" description="Стенд ИФТ блок 1 (мобильный)">
<enabled>true</enabled>
</node>
<node id="mobile.sberbank.ru" description="Стенд ПСИ">
<enabled>true</enabled>
</node>
</nodes>
</param>
<param name="ChangeVisibilityProduct" description="Частичное скрытие продукта">
<type>setting</type>
<enabled>true</enabled>
</param>
<param name="gsHideDeposits" description="Полное скрытие депозитов">
<type>setting</type>
<enabled>true</enabled>
</param>
<param name="gsHideIMs" description="Полное скрытие металлических счетов">
<type>setting</type>
<enabled>true</enabled>
</param>
<param name="gsHideProducts" description="Полное скрытие карт">
<type>setting</type>
<enabled>true</enabled>
</param>
<param name="TariffDebitCard" description="Тариф карты">
<type>service</type>
<enabled>true</enabled>
<link>
https://stat.online.sberbank.ru/PhizIC-res/mapicfg/card_tariffs.xml
</link>
<nodes>
<node id="node0.online.sberbank.ru">
<enabled>true</enabled>
</node>
<node id="node1.online.sberbank.ru">
<enabled>true</enabled>
</node>
<node id="node2.online.sberbank.ru">
<enabled>true</enabled>
</node>
<node id="node3.online.sberbank.ru">
<enabled>true</enabled>
</node>
<node id="node4.online.sberbank.ru">
<enabled>true</enabled>
</node>
<node id="greenfield1.online.sberbank.ru">
<enabled>true</enabled>
</node>
<node id="greenfield2.online.sberbank.ru">
<enabled>true</enabled>
</node>
<node id="mobile.sberbank.ru">
<enabled>true</enabled>
</node>
<node id="ift-node1.testonline.sberbank.ru">
<enabled>true</enabled>
</node>
<node id="ift-node2.testonline.sberbank.ru">
<enabled>true</enabled>
</node>
<node id="ift-node1-mp.testonline.sberbank.ru">
<enabled>true</enabled>
</node>
<node id="ift-node2-mp.testonline.sberbank.ru">
<enabled>true</enabled>
</node>
<node id="psinode2.testonline.sberbank.ru">
<enabled>true</enabled>
</node>
<node id="psinode1.testonline.sberbank.ru">
<enabled>true</enabled>
</node>
<node id="194.186.207.23">
<enabled>true</enabled>
</node>
</nodes>
</param>
<param name="P2POverseasCardTransfer" description="Международный карточный перевод">
<type>list</type>
<enabled>true</enabled>
<nodes>
<node id="node0.online.sberbank.ru">
<enabled>false</enabled>
</node>
<node id="node1.online.sberbank.ru">
<enabled>false</enabled>
</node>
<node id="node2.online.sberbank.ru">
<enabled>false</enabled>
</node>
<node id="node3.online.sberbank.ru">
<enabled>false</enabled>
</node>
<node id="greenfield1.online.sberbank.ru">
<enabled>false</enabled>
</node>
<node id="greenfield2.online.sberbank.ru">
<enabled>false</enabled>
</node>
<node id="194.186.207.23">
<enabled>true</enabled>
</node>
<node id="mobile.sberbank.ru">
<enabled>false</enabled>
</node>
<node id="ift-node0.testonline.sberbank.ru">
<enabled>true</enabled>
</node>
<node id="ift-node1.testonline.sberbank.ru">
<enabled>true</enabled>
</node>
<node id="ift-node2.testonline.sberbank.ru">
<enabled>false</enabled>
</node>
<node id="ift-node0-mp.testonline.sberbank.ru">
<enabled>true</enabled>
</node>
<node id="ift-node1-mp.testonline.sberbank.ru">
<enabled>true</enabled>
</node>
<node id="ift-node2-mp.testonline.sberbank.ru">
<enabled>false</enabled>
</node>
<node id="10.21.152.7">
<enabled>true</enabled>
</node>
</nodes>

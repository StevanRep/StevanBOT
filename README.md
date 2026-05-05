*** READ-ME  ***

RPA_Nubank_Sales_Dispacher
RPA_Nubank_Sales_Performer

Uipath Studio version - 2026.0.192 STS

Pacotes:
Uipath.WebAPI.Activities v2.4.0
Uipath.System.Activities v26.2.5
Uipath.Excel.Activities v3.5.1
Uipath.PDF.Activities v4.1.0


*** Info ***

Para o funcionamento correto do dispacher e performer, é necessário adicionar os seguintes itens no orquestrador:

Queue:
RPA_Nubank_Sales_Queue

Assets:			  		Type:		Value: 

AnosPermitidos				Text		2018,2019,2020,2021
API_CepUrl				Text		https://viacep.com.br/ws/
API_URLCambio				Text		https://economia.awesomeapi.com.br/json/last/
FileName_SalesList			Text		Sales List.pdf
FileName_SalesReport_Template		Text		Sales Report_Template
FileName_VendorList			Text		Vendor List.xlsx
Filepath_Errors				Text		\NubankCaseErrors\Relatório de Erros Encontrados.xlsx
Invoice_Message				Text		Please, GENERATE INVOICES by
SheetName_Template			Text		{ID_VENDOR}
SheetName_VendorList			Text		Vendor list

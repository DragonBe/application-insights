# Azure Application Insights

This Azure Application Insights PHP package offers you a convenient way to send metrics, events, and queries to [Azure Application Insights].

It is based of [microsoft/ApplicationInsights-PHP] library created by [Jakub Oleksy], but was abandoned somewhere in 2019. Since I need to provide telemetery in my PHP applications on Azure, I'd like to restart this project applying all the good things PHP has to offer.

This package makes use of the [Azure Application Insights REST API] to send telemetry to [Azure Application Insights] monitoring service.

[Jakub Oleksy]: https://github.com/JakubOleksy
[Microsoft]: https://www.microsoft.com 
[Azure Application Insights]: https://docs.microsoft.com/nl-nl/azure/azure-monitor/app/app-insights-overview
[microsoft/ApplicationInsights-PHP]: https://github.com/microsoft/ApplicationInsights-PHP
[Azure Application Insights REST API]: https://dev.applicationinsights.io/
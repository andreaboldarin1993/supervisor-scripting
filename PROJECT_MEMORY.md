####### PROJECT_MEMORY.md
####### PROJECT STATE
- Script analizzati
- Script WorkflowScriptBase (corrente)
- Script Workflow Eurocontrol Supervisor Login
- Script Workflow Base Alarm
- Script Workflow Camera/Event Information (corrente analisi)
- Script Workflow Camera/Event Information Extended
- Script Workflow Camera/Event Information (nuovo script)
- Script Workflow Camera/Event Information Export

####### Stato corrente
7 script analizzati

####### Changelog
- Confermato OnLoaded con ClientUi.LoadViewerViews(ImTableSettings)
- Confermato utilizzo StringVariable["ViewerTableSettingsId"]
- Confermato OnControlValueChanged(string,string)
- Confermato OnAllRequiredValuesAvailable()
- Confermato Event.SetPriority(int) con valore 600 e 50
- Confermato Ack() e Complete()
- Confermato Datapoint.FindLocationDrawing()
- Confermato Datapoint.FindDrawings()
- Confermato Datapoint.PropertyValue(...).ValueString
- Confermato PlaySound(Guid,bool)
- Confermato StopAllSounds()
- Confermato RunPopupMacro(Guid)
- Confermato AddReportItem(string,string,string,Guid,...)

####### Problemi aperti
- Precedenza logica LINQ non verificabile
- Comportamento Datapoint.PropertyValue(...) non completamente verificabile
- Significato parametri Datapoint.Control(...) non verificabile

####### Decisioni confermate
- Nessuna

####### TODO
- Analizzare ulteriori script

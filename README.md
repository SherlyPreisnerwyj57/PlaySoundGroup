# PlaySoundGroup
PlaySoundGroup("sound1|sound2|sound3") While 1     $PlaySoundGroup = PlaySoundGroup()     If $PlaySoundGroup = 1 Then         ToolTip("Sounds Playing")     ElseIf $PlaySoundGroup = 0 Then         MsgBox(0,"","Sounds Stopped")         Exit     EndIf     Sleep(50) WEnd

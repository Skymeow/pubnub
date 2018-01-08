`self`

`.client`

`.historyForChannel`

`("my_channel",`

`start`

`:`

`nil`

`,`

`end`

`:`

`nil`

`,`

`limit`

`:`

`3`

`,`

`reverse`

`: true,`

`withCompletion`

`: { (result, status)`

`in`

`if`

`status ==`

`nil`

`{`

`/**`

`Handle downloaded history using:`

`result.data.start - oldest message time stamp in response`

`result.data.end - newest message time stamp in response`

`result.data.messages - list of messages`

`*/`

`}`

`else`

`{`


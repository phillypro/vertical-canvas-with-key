# vertical-canvas-with-key

update stream key with websocket vendor request




    update_stream_key = {
        "op": 6,
        "d": {
            "requestType": "CallVendorRequest",
            "requestId": "someRandomId",
            "requestData": {
                "vendorName": "aitum-vertical-canvas",
                "requestType": "update_stream_key",
                "requestData":  {"stream_key": "examplekey12345678", },
            },
        },
    }
    ws.send(json.dumps(update_stream_key))

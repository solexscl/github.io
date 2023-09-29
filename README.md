<!DOCTYPE html>
<html>
<head>
    <meta charset="utf-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Haz llamadas gratis con illamadas</title>
    <link rel="icon" href="/public/images/calls-online/favicon.png">
    <link href="/public/stylesheets/phone-calls-online.css" rel="stylesheet" type="text/css">
    <script>
        var phoneSettings = { 'bgColor': '#2c2c2c', 'width': '288', 'height': '220' };
        var codecName = 'NellyMoser';
        var paidCall = false;
        var useFlashLogger = false;
        var domainParam = 'ILLAMADAS';
        var webRtcEnabled = true;
    </script>
    <script type="text/javascript" src="/public/javascripts/compress-phone-widget-23112018.js"></script>
</head>
<body>
    <div id="phone">
        <script type="text/javascript">
            var codecName = 'NellyMoser';
            var useFlashLogger = false;
            var domainParam = 'ILLAMADAS';
            var webRtcEnabled = true;
            var registeredUser = false;
        </script>
        <div id="phone-inner">
            <div id="p-p-wrap">
                <input type="text" id="phone-number" class="phoneNumber" autocomplete="off" />
            </div>
            <div id="message-wrapper" class="infoMessage"></div>
            <div style="overflow: hidden;" class="callHang">
                <div class="p-call-btn call"></div>
                <div class="p-call-btn hang" id="hang"></div>
            </div>
            <div style="overflow: hidden;" id="phone-btn-wrap" class="phoneButton">
                <!-- Aquí puedes incluir los botones para marcar números -->
            </div>
            <div id="wtpCallerObjectWrapper">
                <div id="c2fCaller"></div>
            </div>
            <div id="wait-wrap">
                <div class="cssload-container">
                    <div class="cssload-speeding-wheel"></div>
                </div>
                <div id="wait-timer">00:30</div>
                <div style="text-align: center;margin-top: 50px;">Please wait while we are checking whether your call can be connected.</div>
            </div>
        </div>
    </div>
</body>
</html>



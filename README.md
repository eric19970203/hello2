function doPost() {
    UrlFetchApp.fetch('https://notify-api.line.me/api/notify', {
        'headers': {
            'Authorization': 'Bearer ' + '9GmHYAWXAAgKHn4JguGfTUVwwBlr9pwJ3dSTi049EB4',
        },
        'method': 'post',
        'payload': {
            'message':'測試一下！',
            'stickerPackageId':'1',
            'stickerId':'2'
        }
    });
}

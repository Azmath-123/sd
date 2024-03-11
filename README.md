# sd
fetch('https://sheetdb.io/api/v1/2oiwfuwjqc2m9', {
    method: 'POST',
    headers: {
        'Accept': 'application/json',
        'Content-Type': 'application/json'
    },
    body: JSON.stringify({
        data: [
            {
                'Name': "Mark",
                'PhoneNo': "74635819679",
                'Language':"python",
                'Q1': 18,
                'Q2':13
            }
        ]
    })
})
  .then((response) => response.json())
  .then((data) => console.log(data));


#<taaabs-csv-verify-file># 

`<taaabs-csv-verify-file>` is an element that check if a csv file is error free, according to its csv schema.

Example:

    var tcvf = new TaaabsCsvVerifyFile();
    tcvf.verify( file, csvSchema, progressBar )
      .then(function(data){
        console.log(data);
      })
      .catch(function(data){
        console.log(data)
      }); 

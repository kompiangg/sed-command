# ubah konfigurasi file tanpa pagar
    
    sed -i -e 's/$SEARCH.*=.*/$REPLACE = $VALUE/' $FILE_PATH

# ubah konfigurasi file dengan pagar

    sed -i -e 's/#* *$SEARCH.*=.*/$REPLACE = $VALUE/' $FILE_PATH

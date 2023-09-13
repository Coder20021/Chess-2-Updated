My game Dat I play w/ my fwiends in school for fun. A lot more game mode will be added, you cant help if you dont ask for my permission
TextView LinkButton = (TextView) findViewById(R.id.TextViewID);
LinkButton.setOnClickListener(new View.OnClickListener() {          
        public void onClick(View v) {
            // TODO Auto-generated method stub
                            Uri uri = Uri.parse("[http://www.link.com](https://coder20021.github.io/Chess-2-Updated/Chesss%20(2).html)");
                            Intent openBrowser = new Intent(Intent.ACTION_VIEW, uri);
                            startActivity(openBrowser);
        }
    });


# GUI_Handling

## My submission for GUI Programming.
All four files (Not including README.md) are all related to each other, each one will not work properly if one file is removed.

The loop below is for finding a specific part of the Diary.

              while(rec!=null){
                String[] recAry = rec.split("%");
                String id = recAry[0];
                if(!txtInput.getText().equals("") && id.contains(txtInput.getText())){
                    String[] recAry1 = rec.split("%");
                    String id1 = recAry1[0];
                    String date = recAry1[1];
                    String contentOut = recAry1[2];
                
                    content += id1+" - "+date+" CONTENT:"+
                            "\n-----------------------------------------------------"+
                            "\n"+contentOut+
                            "\n-----------------------------------------------------\n";
                    rec = br.readLine();
                    txtInput.setText("");
                    
                }
              }

Images of working code below:
![image](https://github.com/user-attachments/assets/5532ee93-37dc-4865-b483-6db70a396239)
![image](https://github.com/user-attachments/assets/b31cc061-ef35-436b-91a1-a35a89ffe76b)
![image](https://github.com/user-attachments/assets/5812e147-0884-4b89-b118-9b395b657680)
![image](https://github.com/user-attachments/assets/32420359-0e82-42d1-8cf2-628d50eaec8f)
![image](https://github.com/user-attachments/assets/5e5a95d3-4845-400d-a027-1d2d76ec64df)


Saved Data:
![image](https://github.com/user-attachments/assets/a1eacc41-852f-4dd5-9c35-f625560a5523)

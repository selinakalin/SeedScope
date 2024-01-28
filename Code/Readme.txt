1. Download Python >= 3.8 
2. "pip install -r requirements.txt" in folder
3. ...
	    with open(csv_path, mode='a', newline='') as f:
                writer = csv.DictWriter(f, fieldnames=data.keys())
                if not csv_path.is_file():
                    writer.writeheader()
                writer.writerow(data)
            file_path = 'tohumlar.xlsx'
            sheet_name = 'Sayfa1'
   ... in this block, we should change file path according to "tohumlar.xlsx"

4.  In this line "parser.add_argument('--weights', nargs='+', type=str, default=ROOT / 'C:/Users/Berkay/PycharmProjects/yoloo/yolov5-master/best.pt', help='model path or triton URL')", we should change path according to best.pt file

5. Inthıs line "parser.add_argument('--data', type=str, default=ROOT / 'data/data.yaml', help='(optional) dataset.yaml path')", we should change path according to data.yaml file.

 
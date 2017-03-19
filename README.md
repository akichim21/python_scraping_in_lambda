# python_scraping_in_lambda
python scraping in aws lambda

lambda.jsonのroleを正しい値に変更

## install
pip install python-lambda-local
pip install lambda-uploader

## ローカル実行
python-lambda-local -f lambda_handler -l ./ -t 60 lambda_function.py event.json

## アップロード
lambda-uploader

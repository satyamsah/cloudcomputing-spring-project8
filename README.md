# cloudcomputing-spring-project8

command to run on yarn :

naive-bayes$ spark-submit --master yarn --deploy-mode client --executor-memory 1g --name naivebayes --conf "spark.app.id=naivebayes" naivebayes.py > output.txt

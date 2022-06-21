# sap-vehicle-management-system-for-vehicle-location-sql

sap-vehicle-management-system-for-vehicle-location-sql は、主にエッジアプリケーションにおいて、SAPと連携された 車両位置用車両マネジメントシステムデータ を保存するSQLテーブルを作成するためのレポジトリです。   
sap-vehicle-management-system-for-vehicle-location-sql は、そのままクラウド環境におけるアプリケーションにも、適用可能です。  

## 前提条件  
sap-vehicle-management-system-for-vehicle-locationは、SQL の SAP とのデータ連携にあたり、オンプレミス版である（＝クラウド版ではない）SAPS4HANA API の利用を前提としています。    
クラウド版APIを利用する場合は、ご注意ください。  
https://api.sap.com/api/OP_API_VMSVEHICLELOCATION_0001/overview  
本レポジトリ の sql設定ファイルの内容は、上記URL の API 仕様を前提としています。  

## sqlの設定ファイル
sap-vehicle-management-system-for-vehicle-location には、sqlの設定ファイルとして、以下のファイルが含まれています。  

* sap-vms-vehicle-collection-data.sql（SAP 車両位置用車両マネジメントシステムデータ - 車両マネジメントシステムデータ）  
  
## MySQLのセットアップ / Kubernetesの設定 / SQLテーブルの作成方法  

MySQLのセットアップ / Kubernetesの設定 / 具体的なSQLテーブルの作成方法、については、[mysql-kube](https://github.com/latonaio/mysql-kube)を参照ください。  
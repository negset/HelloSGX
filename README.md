1. 新しいプロジェクト

   Intel SGX Enclave Project  
   名前: Enclave  
   ソリューション名: HelloSGX  
   ソリューションのディレクトリを作成

1. Intel SGX Enclave Project Wizard

   Next > Finish

1. プロジェクト > ソリューションの再ターゲット

1. プロジェクト > プロパティ > デバッグ

   起動するデバッガー: Intel SGX Debugger  
   Working Directory: $(OutDir)

1. ファイル > 追加 > 新しいプロジェクト

   空のプロジェクト  
   名前: App

1. Appプロジェクト右クリック > Intel SGX Configuration > Import Enclave

   Enclave > Enclave.edl

1. プロジェクト > 新しい項目の追加

   App.cpp  
   error_print.cpp  
   error_print.h

1. 以下を編集

   App.cpp  
   error_print.cpp  
   error_print.h  
   Enclave.cpp  
   Enclave.edl

1. ビルド > ソリューションのビルド
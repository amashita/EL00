# EL00


    typings install github-electron --ambient
    
    typings init
    
    
環境変数のpathから削除する
原因はVSのアドオンとして入ってるTypeScriptコンパイラのパスが環境変数で設定されている
システム環境変数のpathから以下エントリを削除
C:\Program Files (x86)\Microsoft SDKs\TypeScript\


　
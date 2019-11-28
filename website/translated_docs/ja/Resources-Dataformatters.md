---
id: custom-data-formatters
title: データフォーマッター
---


<div class = "tips"> 

**はじめに**

1. To use a custom formatter, the first thing you'll need to do is create a `YourDatabase.4dbase/Resources/Mobile/formatters` folder.

2. フォーマッターは，このフォルダーの中にインストールします。</div> 

<div style="height: auto;">
  <table>
    <col width="50%"> <col width="50%"> 
    
    <tr>
      <td style="height: auto; vertical-align: middle;text-align: center; border-color: #FFFFFF;background-color: #FFFFFF">
        <img style="max-height: 300px; opacity: 0.2" src="https://raw.githubusercontent.com/4d-for-ios/formatter-Mail/master/formatter.png" />
      </td>
      
      <td style="height: auto; vertical-align: middle;border-color: #FFFFFF;background-color: #FFFFFF">
        <h1 style="margin-top: 10px; font-size:22px">
          メール
        </h1>
        
        <ul style="font-size:16px">
          <li>
            <strong>フォーマット:</strong> テキスト → メール
          </li>
          <li>
            <strong>動作:</strong> メールアプリを開く
          </li>
          <li>
            <strong>タイプ:</strong> Swift フォーマッター
          </li>
          <div style="text-align: center; margin-top: 40px;">
            <p>
              <a class="button" style="width: 50%; font-size: 11px" href="https://github.com/4d-for-ios/formatter-Mail/releases/latest/download/formatter-Mail.zip">ダウンロード</a>
            </p>
          </div></td> </tr> 
          
          <tr>
            <td style="height: auto; vertical-align: middle;border-color: #FFFFFF;background-color: #FFFFFF">
              <h1 style="margin-top: 10px; font-size:22px">
                URL
              </h1>
              
              <ul style="font-size:16px">
                <li>
                  <strong>フォーマット:</strong> テキスト → URL
                </li>
                <li>
                  <strong>動作:</strong> ブラウザアプリを開く
                </li>
                <li>
                  <strong>タイプ:</strong> Swift フォーマッター
                </li>
                <div style="text-align: center; margin-top: 40px;">
                  <p>
                    <a class="button" style="width: 50%; font-size: 11px" href="https://github.com/4d-for-ios/formatter-Url/releases/latest/download/formatter-Url.zip">ダウンロード</a>
                  </p>
                </div></td> 
                
                <td style="height: auto; vertical-align: middle;text-align: center; border-color: #FFFFFF;background-color: #FFFFFF">
                  <img style="max-height: 300px; opacity: 0.2" src="https://raw.githubusercontent.com/4d-for-ios/formatter-Url/master/formatter.png" />
                </td></tr> 
                
                <tr>
                  <td style="height: auto; vertical-align: middle;text-align: center; border-color: #FFFFFF">
                    <img style="max-height: 300px; opacity: 0.2" src="https://raw.githubusercontent.com/4d-for-ios/formatter-Phone/master/formatter.png" />
                  </td>
                  
                  <td style="height: auto; vertical-align: middle;border-color: #FFFFFF">
                    <h1 style="margin-top: 10px; font-size:22px">
                      電話番号
                    </h1>
                    
                    <ul style="font-size:16px">
                      <li>
                        <strong>フォーマット:</strong> 数字 → 電話番号
                      </li>
                      <li>
                        <strong>動作:</strong> 電話をかける
                      </li>
                      <li>
                        <strong>タイプ:</strong> Swift フォーマッター
                      </li>
                      <div style="text-align: center; margin-top: 40px;">
                        <p>
                          <a class="button" style="width: 50%; font-size: 11px" href="https://github.com/4d-for-ios/formatter-Phone/releases/latest/download/formatter-Phone.zip">ダウンロード</a>
                        </p>
                      </div></td> </tr> 
                      
                      <tr>
                        <td style="height: auto; vertical-align: middle;border-color: #FFFFFF;background-color: #FFFFFF">
                          <h1 style="margin-top: 10px; font-size:22px">
                            住所
                          </h1>
                          
                          <ul style="font-size:16px">
                            <li>
                              <strong>フォーマット:</strong> テキスト → 住所
                            </li>
                            <li>
                              <strong>動作:</strong> 地図アプリを開く
                            </li>
                            <li>
                              <strong>タイプ:</strong> Swift フォーマッター
                            </li>
                            <div style="text-align: center; margin-top: 40px;">
                              <p>
                                <a class="button" style="width: 50%; font-size: 11px" href="https://github.com/4d-for-ios/formatter-Address/releases/latest/download/formatter-Address.zip">ダウンロード</a>
                              </p>
                            </div></td> 
                            
                            <td style="height: auto; vertical-align: middle;text-align: center; border-color: #FFFFFF;background-color: #FFFFFF">
                              <img style="max-height: 300px; opacity: 0.2" src="https://raw.githubusercontent.com/4d-for-ios/formatter-Address/master/formatter.png" />
                            </td></tr> 
                            
                            <tr>
                              <td style="height: auto; vertical-align: middle;text-align: center; border-color: #FFFFFF">
                                <img style="max-height: 300px; opacity: 0.2" src="https://raw.githubusercontent.com/4d-for-ios/formatter-IntToImage/master/formatter.png" />
                              </td>
                              
                              <td style="height: auto; vertical-align: middle;border-color: #FFFFFF">
                                <h1 style="margin-top: 10px; font-size:22px">
                                  整数から画像
                                </h1>
                                
                                <ul style="font-size:16px">
                                  <li>
                                    <strong>フォーマット:</strong> 整数 → 画像
                                  </li>
                                  <li>
                                    <strong>タイプ:</strong> 単純なフォーマッター
                                  </li>
                                  <div style="text-align: center; margin-top: 40px;">
                                    <p>
                                      <a class="button" style="width: 50%; font-size: 11px" href="https://github.com/4d-for-ios/formatter-IntegerToImage/releases/latest/download/formatter-IntegerToImage.zip">ダウンロード</a>
                                    </p>
                                  </div></td> </tr> 
                                  
                                  <tr>
                                    <td style="height: auto; vertical-align: middle;border-color: #FFFFFF;background-color: #FFFFFF">
                                      <h1 style="margin-top: 10px; font-size:22px">
                                        整数から文字列
                                      </h1>
                                      
                                      <ul style="font-size:16px">
                                        <li>
                                          <strong>フォーマット:</strong> 整数 → 文字列
                                        </li>
                                        <li>
                                          <strong>タイプ:</strong> 単純なフォーマッター
                                        </li>
                                        <div style="text-align: center; margin-top: 40px;">
                                          <p>
                                            <a class="button" style="width: 50%; font-size: 11px" href="https://github.com/4d-for-ios/formatter-IntToString/releases/latest/download/formatter-IntToString.zip">ダウンロード</a>
                                          </p>
                                        </div></td> 
                                        
                                        <td style="height: auto; vertical-align: middle;text-align: center; border-color: #FFFFFF;background-color: #FFFFFF">
                                          <img style="max-height: 300px; opacity: 0.2" src="https://raw.githubusercontent.com/4d-for-ios/formatter-IntToString/master/formatter.png" />
                                        </td></tr> 
                                        
                                        <tr>
                                          <td style="height: auto; vertical-align: middle;text-align: center; border-color: #FFFFFF">
                                            <img style="max-height: 300px; opacity: 0.2" src="https://raw.githubusercontent.com/4d-for-ios/formatter-TextToImage/master/formatter.png" />
                                          </td>
                                          
                                          <td style="height: auto; vertical-align: middle;border-color: #FFFFFF">
                                            <h1 style="margin-top: 10px; font-size:22px">
                                              テキストから画像
                                            </h1>
                                            
                                            <ul style="font-size:16px">
                                              <li>
                                                <strong>フォーマット:</strong> テキスト → 画像
                                              </li>
                                              <li>
                                                <strong>タイプ:</strong> 単純なフォーマッター
                                              </li>
                                              <div style="text-align: center; margin-top: 40px;">
                                                <p>
                                                  <a class="button" style="width: 50%; font-size: 11px" href="https://github.com/4d-for-ios/formatter-TextToImage/releases/latest/download/formatter-TextToImage.zip">ダウンロード</a>
                                                </p>
                                              </div></td> </tr> 
                                              
                                              <tr>
                                                <td style="height: auto; vertical-align: middle;border-color: #FFFFFF;background-color: #FFFFFF">
                                                  <h1 style="margin-top: 10px; font-size:22px">
                                                    テキストから文字列
                                                  </h1>
                                                  
                                                  <ul style="font-size:16px">
                                                    <li>
                                                      <strong>フォーマット:</strong> テキスト → 文字列
                                                    </li>
                                                    <li>
                                                      <strong>タイプ:</strong> 単純なフォーマッター
                                                    </li>
                                                    <div style="text-align: center; margin-top: 40px;">
                                                      <p>
                                                        <a class="button" style="width: 50%; font-size: 11px" href="https://github.com/4d-for-ios/formatter-TextToString/releases/latest/download/formatter-TextToString.zip">ダウンロード</a>
                                                      </p>
                                                    </div></td> 
                                                    
                                                    <td style="height: auto; vertical-align: middle;text-align: center; border-color: #FFFFFF;background-color: #FFFFFF">
                                                      <img style="max-height: 300px; opacity: 0.2" src="https://raw.githubusercontent.com/4d-for-ios/formatter-TextToString/master/formatter.png" />
                                                    </td></tr> 
                                                    
                                                    <tr>
                                                      <td style="height: auto; vertical-align: middle;text-align: center; border-color: #FFFFFF">
                                                        <img style="max-height: 300px; opacity: 0.2" src="https://raw.githubusercontent.com/4d-for-ios/formatter-BoolToImage/master/formatter.png" />
                                                      </td>
                                                      
                                                      <td style="height: auto; vertical-align: middle;border-color: #FFFFFF">
                                                        <h1 style="margin-top: 10px; font-size:22px">
                                                          ブールから画像
                                                        </h1>
                                                        
                                                        <ul style="font-size:16px">
                                                          <li>
                                                            <strong>フォーマット:</strong> ブール → 画像
                                                          </li>
                                                          <li>
                                                            <strong>タイプ:</strong> 単純なフォーマッター
                                                          </li>
                                                          <div style="text-align: center; margin-top: 40px;">
                                                            <p>
                                                              <a class="button" style="width: 50%; font-size: 11px" href="https://github.com/4d-for-ios/formatter-BoolToImage/releases/latest/download/formatter-BoolToImage.zip">ダウンロード</a>
                                                            </p>
                                                          </div></td> </tr> 
                                                          
                                                          <tr>
                                                            <td style="height: auto; vertical-align: middle;border-color: #FFFFFF;background-color: #FFFFFF">
                                                              <h1 style="margin-top: 10px; font-size:22px">
                                                                絵文字
                                                              </h1>
                                                              
                                                              <ul style="font-size:16px">
                                                                <li>
                                                                  <strong>フォーマット:</strong> ブール・実数・整数 → 絵文字
                                                                </li>
                                                                <li>
                                                                  <strong>タイプ:</strong> 単純なフォーマッター
                                                                </li>
                                                                <div style="text-align: center; margin-top: 40px;">
                                                                  <p>
                                                                    <a class="button" style="width: 50%; font-size: 11px" href="https://github.com/4d-for-ios/formatter-Emoji/releases/latest/download/formatter-Emoji.zip">ダウンロード</a>
                                                                  </p>
                                                                </div></td> 
                                                                
                                                                <td style="height: auto; vertical-align: middle;text-align: center; border-color: #FFFFFF;background-color: #FFFFFF">
                                                                  <img style="max-height: 300px; opacity: 0.2" src="https://raw.githubusercontent.com/4d-for-ios/formatter-Emoji/master/formatter.png" />
                                                                </td></tr> 
                                                                
                                                                <tr>
                                                                  <td style="height: auto; vertical-align: middle;text-align: center; border-color: #FFFFFF">
                                                                    <img style="max-height: 300px; opacity: 0.2" src="https://raw.githubusercontent.com/4d-for-ios/formatter-HTML/master/formatter.png" />
                                                                  </td>
                                                                  
                                                                  <td style="height: auto; vertical-align: middle;border-color: #FFFFFF">
                                                                    <h1 style="margin-top: 10px; font-size:22px">
                                                                      HTML
                                                                    </h1>
                                                                    
                                                                    <ul style="font-size:16px">
                                                                      <li>
                                                                        <strong>Format:</strong> Text ⟶ html
                                                                      </li>
                                                                      <li>
                                                                        <strong>Type:</strong> Swift formatter
                                                                      </li>
                                                                      <div style="text-align: center; margin-top: 40px;">
                                                                        <p>
                                                                          <a class="button" style="width: 50%; font-size: 11px" href="https://github.com/4d-for-ios/formatter-HTML/releases/latest/download/formatter-HTML.zip">DOWNLOAD</a>
                                                                        </p>
                                                                      </div></td> </tr> </table> </div>
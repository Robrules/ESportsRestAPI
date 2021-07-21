# SCD2_2021_Exam
Exam Work: Robert Bannayan

My PandaAPI token: uUQthJW-8MGfjMbSsLyqi9TJaA4x-1seDZO3ikVi5ePHuJFAG8Y
My ClientID: 4746b348d78dae2

Extension Requirements Met:
   Commit Url: https://github.sydney.edu.au/rban8770/SCD2_2021_Exam/commit/840f1c5afc175c8db926c222d161a2ec55922b91

GRADE Requirements Met (CREDIT completed):
    PASS: https://github.sydney.edu.au/rban8770/SCD2_2021_Exam/commit/c9e39a172833a13021921bccc06766deca60c192
    CREDIT: https://github.sydney.edu.au/rban8770/SCD2_2021_Exam/commit/bf767562e1fb5234c9f858d095529ee92616931a

Important Notes:
    - You must provide an authorisation token for the pandaScore API (input API) and clientID for the Imgur API
      (output API) on the main menu in the GUI. If there are any issues with your details, you can use mine
      (provided above)
    - You must also provide a valid year and press confirm to be able to login
    - The generated report is also printed to standard output so you can view it when using a dummy output API. This is
      also so that in (rare) circumstances where the report is very long, you will still be able to see the report if
      your phone can't detect the detailed Qrcode image
    - The imgur link to the QR code is also printed to standard output for ease of use to access (instead of retyping
      the link displayed on the GUI)
    - There are slight loading times when logging in using the real input Api, and clicking on each league due to
      generating the image for that league
    - Deciding to use cache data is done on the main screen with the button (click to make it green and use cache data).
      If you use cache data on your first run of the program there will be no leagues to display as there is no data
      cached. Restart the application after displaying leagues without the cache, and then choose the cache option to
      use stored cache data. Then you will see the stored league data.

References:

    JsonMapper:
    The 'map' method was inspired/used from a stack overflow response by user987339
    URL: https://stackoverflow.com/questions/19760138/parsing-json-in-java-without-knowing-json-format

    QRCodeGenerator:
    The 'generateQrCodeImage' method was taken from a Callicoder tutorial under the heading 'Program to generate QR Code'
    URL: https://www.callicoder.com/generate-qr-code-in-java-using-zxing/

    GameWindow
    The listener event added to scroll bar was taken from a stack overflow response by Sarfaraz Khan
    URL: https://stackoverflow.com/questions/30971407/javafx-is-it-possible-to-have-a-scroll-bar-in-vbox/47581633

    CacheDb and CacheDb/PandaFacadeTests
    The connection method in CacheDb and the @After method in cacheDbtests and pandaFacadetests were taken from a previous
    group assessment from Soft2412 Sem 2 2020




RED-GREEN-REFACTOR Links

    Register method in PandaFacade
    RED: https://github.sydney.edu.au/rban8770/SCD2_2021_Exam/commit/4c0f69ed7593da6ad363ee0f650d15b960d81083
    GREEN: https://github.sydney.edu.au/rban8770/SCD2_2021_Exam/commit/1201e98d08f2c10439aa155ee66cf105c101f7d7
    REFACTOR (altered exception handling): https://github.sydney.edu.au/rban8770/SCD2_2021_Exam/commit/6b7e0fb3bb45d6f38c8fdb5de2efc356f7eb1169
    REFACTOR (mocked pandaDb) https://github.sydney.edu.au/rban8770/SCD2_2021_Exam/commit/b9c85c191fd4683041090334cec2a68700ab5070

    StoreLeagues method in PandaFacade
    RED: https://github.sydney.edu.au/rban8770/SCD2_2021_Exam/commit/a01d8cd90ed508ad373bbb24fb02338a50ee2547
    GREEN: https://github.sydney.edu.au/rban8770/SCD2_2021_Exam/commit/4a241cbf3f4405327d56e2648d3fe42ea3a46900
    REFACTOR (mocked pandaDb) https://github.sydney.edu.au/rban8770/SCD2_2021_Exam/commit/b9c85c191fd4683041090334cec2a68700ab5070
    RED (changing method implementation) https://github.sydney.edu.au/rban8770/SCD2_2021_Exam/commit/f93b93c94c9bf25ca282653f13a96b98c0529906
    GREEN:https://github.sydney.edu.au/rban8770/SCD2_2021_Exam/commits/master

    GetLeagues method in PandaFacade
    RED: https://github.sydney.edu.au/rban8770/SCD2_2021_Exam/commit/deb3b8a26f2b51a5af0ea11bdac2566dbbd1524c
    GREEN: https://github.sydney.edu.au/rban8770/SCD2_2021_Exam/commit/beda4a8518a1deaae836e9212886561b97235108
    REFACTOR (mocked pandaDb) https://github.sydney.edu.au/rban8770/SCD2_2021_Exam/commit/b9c85c191fd4683041090334cec2a68700ab5070

    Register method in ImgurFacade
    RED: https://github.sydney.edu.au/rban8770/SCD2_2021_Exam/commit/b333921384aa443075a2ccf25caaa7db2a212f60
    GREEN: https://github.sydney.edu.au/rban8770/SCD2_2021_Exam/commit/65ed0ebc78928edc02892fff4d1389b9d6bb2ec8

    UploadImage method in ImgurFacade
    RED: https://github.sydney.edu.au/rban8770/SCD2_2021_Exam/commit/ff5e53fc5a14d5b906276b7a265ddbba80bb2f73
    GREEN: https://github.sydney.edu.au/rban8770/SCD2_2021_Exam/commit/541f5626a226c20ffec41613295ea22dfacd66ae

    RegisterPanda method in MainFacade
    RED: https://github.sydney.edu.au/rban8770/SCD2_2021_Exam/commit/7c324c63d0c33d0176310646b215083f70bee366
    GREEN: https://github.sydney.edu.au/rban8770/SCD2_2021_Exam/commit/6f50feb23ca5766bade825addbcedc3c8cf9d26d

    StoreLeagues method in MainFacade
    RED: https://github.sydney.edu.au/rban8770/SCD2_2021_Exam/commit/83cdb116c35408354648d022fcadd7dfda8418e4
    GREEN: https://github.sydney.edu.au/rban8770/SCD2_2021_Exam/commit/3afc9679774e631f3fc26a1cdd8c5364a08d5e4e

    GetLeagues method in MainFacade
    RED: https://github.sydney.edu.au/rban8770/SCD2_2021_Exam/commit/0f704abd85a8a68bd346abc7f6f55243bf14d771
    GREEN: https://github.sydney.edu.au/rban8770/SCD2_2021_Exam/commit/888c5712629e6948d9daa16edd8ffaf7463bcb5c

    RegisterClientId method in MainFacade
    RED: https://github.sydney.edu.au/rban8770/SCD2_2021_Exam/commit/01bd62ab9f851163720bb38b5f5bad7ad93c0bbd
    GREEN: https://github.sydney.edu.au/rban8770/SCD2_2021_Exam/commit/999b84a74f0435c704fde4c617fbb05d0aebfd69

    UploadImage method in MainFacade
    RED: https://github.sydney.edu.au/rban8770/SCD2_2021_Exam/commit/ac141a9b5e34b571834c587aec3808d7863e9058
    GREEN: https://github.sydney.edu.au/rban8770/SCD2_2021_Exam/commit/b3c90bd205bc1e269fb04b3e59dcb0c2f6284d92

    GenerateReport method in MainFacade
    RED: https://github.sydney.edu.au/rban8770/SCD2_2021_Exam/commit/b578504bcd7a87c174206f4a614b47da2039be8e
    GREEN: https://github.sydney.edu.au/rban8770/SCD2_2021_Exam/commit/9d89c72cbca0b2068217d94f5ecca62dcce3935f

    MakeQrCode method in MainFacade
    RED: https://github.sydney.edu.au/rban8770/SCD2_2021_Exam/commit/02a583f58e07193c4fb5918e8f0c27164ba48005
    GREEN: https://github.sydney.edu.au/rban8770/SCD2_2021_Exam/commits/master

    Create, Insert, getCachedLeagues method in CacheDb
    RED: https://github.sydney.edu.au/rban8770/SCD2_2021_Exam/commit/c0e92e0b2d915c41133eb93edac41c73a8d30341
    GREEN: https://github.sydney.edu.au/rban8770/SCD2_2021_Exam/commit/2c6c7bdb3e8df1fe3f75882455e3b5c75692d0ed

    EXTENSION

    isModifiedAfter method in League class
    RED: https://github.sydney.edu.au/rban8770/SCD2_2021_Exam/commit/fb22dbbd6cb4dd5bb2e39caa838b9e284a5cd43a
    GREEN: https://github.sydney.edu.au/rban8770/SCD2_2021_Exam/commit/6871a0dcb4b398c00b1f190476955a8aebe5b2d5

    New functionality of GenerateReport method in MainFacade
    RED: https://github.sydney.edu.au/rban8770/SCD2_2021_Exam/commit/7b8f7f14fb2d829767732524023421048d6ec4b8
    GREEN: https://github.sydney.edu.au/rban8770/SCD2_2021_Exam/commit/7f8d2967343c38c0f8ea92ccc83eedd45fa3811b

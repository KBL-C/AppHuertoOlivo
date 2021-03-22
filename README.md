# AppHuertoOlivo

## Creación de código desde 0
#### Este código se encarga de crear una ventana de carga conde aparece el icono de app, durante el tiempo que tarde ejecutar la aplicacon y acceder a la ventana de inicio
<activity android:name=".MainActivity"
            android:theme="@style/SplashThem"> //
            <intent-filter>
                <action android:name="android.intent.action.MAIN" />

                <category android:name="android.intent.category.LAUNCHER" />
            </intent-filter>
        </activity>
        <style name="SplashThem" parent="Theme.HuertoOlivo">
        <item name="android:windowBackground">@drawable/ventanadecarga</item>

    </style>

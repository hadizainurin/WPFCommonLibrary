# Common Library
Common resources used for WPF project in Visual Studio.

Please don't forget to add this line in your App.xaml 
'''
<Application.Resources>
        <ResourceDictionary>
            <ResourceDictionary.MergedDictionaries>
                <ResourceDictionary Source="Styles/ButtonStyles.xaml" />
                <ResourceDictionary Source="Styles/TextBoxStyles.xaml" />
            </ResourceDictionary.MergedDictionaries>
        </ResourceDictionary>
    </Application.Resources>
'''

# MVVM Bindings for .NET iOS and .NET Android

At the moment there is no library out there that allows you to create bindings between your `ViewModel` and your iOS / Android view (UIViewController / Fragments) with **weak reference** support for **.NET for iOS** and **.NET for Android**.

[MVVM Light Toolkit](https://github.com/lbugnion/mvvmlight) was great at providing this via the `SetBinding` and `SetCommand` APIs for Xamarin.iOS and Xamarin.Android - but as many of you know, the project has been archived and some of its core APIs were moved to [MVVM Toolkit](https://learn.microsoft.com/en-gb/dotnet/communitytoolkit/mvvm/). The bindings weren't included in the migration though.

This project copied the original source code from [MVVM Light Toolkit](https://github.com/lbugnion/mvvmlight) and made a few tweaks (which can be reviewed in the commit history on this repo) to make it compatible with **.NET for iOS** and **.NET for Android**.

> I don't have availability to publish this project as a nuget or to actively maintain it.
>
> If you want to use this project you can simply download the source code and add it to your .sln as an additional project. This is also how we use it internally in our company.
>
> You can find a sample application using the bindings [here](https://github.com/FortechRomania/xamarin-training-sample-app).
>
> If you'd like this to be adopted by the team running the official [.NET Community Toolkit](https://github.com/CommunityToolkit/dotnet) then please engage with this issue [MVVM Bindings for .NET iOS and .NET Android](https://github.com/CommunityToolkit/dotnet/issues/363).

## License

Under [MIT License](LICENSE) (the original license from the [MVVM Light Toolkit](https://github.com/lbugnion/mvvmlight) repo)

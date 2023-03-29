## Breeders of the Nephelym Mods

I will share the source soon just want to fix and cleanup some errors but its in a working state now.

Only mod available is the "**BiggusDickus**" mod (*just makes your friend bigger when running around*)

To install it navigate to the game folder then follow the path "**\Breeders of the Nephelym Alpha\OBF\Binaries\Win64**"
you can rename the existing xinput1_3 to anything if you want to keep it as a backup but you need to replace it with the version from here you can then place the mods folder there.

If you think this is a noobie way of doing things then deal with it cause i usually dont make stuff with c++ or even share what i make.

You can place any dll in the mods folder and it will get loaded and will attempt to call a Method called "**Info**" so if you make your own this should be enough.

    extern "C" __declspec(dllexport) void Info()
    {
        std::cout << "BiggusDickus!" << std::endl;
    }

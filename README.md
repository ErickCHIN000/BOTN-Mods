## Breeders of the Nephelym Mods

I will share the source soon just want to fix and cleanup some errors but its in a working state now.

Only mod available is the "**BiggusDickus**" mod (*just makes your friend bigger when running around*)

You can place any dll in the mods folder and it will get loaded and will attempt to call a Method called "**Info**" so if you make your own this should be enough.

    extern "C" __declspec(dllexport) void Info()
    {
        std::cout << "BiggusDickus!" << std::endl;
    }

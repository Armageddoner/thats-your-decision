# Sprint 1 - Progress Check

## What I've Learned

I messed around with the IntelliJ IDE and decided it was a great IDE to use for this project due to its easy version control access and its intuitive tools.

I followed the NeoForge Modding tutorial to the second episode and learned how to create an item and assign its texture. Following through, JavaScript really isn't that different from C#, save for some other things.

## What I'm going to do next

I'm going to continue the tutorial to get a better understanding of how modding in Minecraft works. By the end of it, I should have a grasp on how to interact with or create features in Minecraft.

Below is a segment of what I've done.

-# Snippet from ModItems.java
```
 private void addCreative(BuildCreativeModeTabContentsEvent event) {
        if (event.getTabKey() == CreativeModeTabs.INGREDIENTS) {
            event.accept(ModItems.COGITO);
            event.accept(ModItems.Enkephalin);
        }
    }
```

-# Item names en-us.json
```
{
  "item.thatsyourdecisionllc.cogito": "Cogito",
  "item.thatsyourdecisionllc.enkephalin": "Enkephalin"
}
```

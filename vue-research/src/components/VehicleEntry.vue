<template>
    <div>
        <!-- TODO lets get the other two dropdowns 
            before we tackle loading data into the controls from the back end 
        -->
        <form>
            <select name="Year">
                <option value="2023">2023</option>
                <option value="2022">2022</option>
                <option value="2021">2021</option>
                <option value="2020">2020</option>
            </select>
            <select name="Make">
                <option value="Chevrolet">Chevrolet</option>
                <option value="Dodge">Dodge</option>
                <option value="Ford">Ford</option>
                <option value="Nissan">Nissan</option>
            </select>
            <!-- this select is dependent on the make -->
            <!--  Lets have this control appear after a yeat and make is eslected -->
            <select name="Model">
                <option value="2023">2023</option>
                <option value="2022">2022</option>
                <option value="2021">2021</option>
                <option value="2020">2020</option>
            </select>
            <input type="submit" value="Submit"/>
        </form>
    </div>
</template>

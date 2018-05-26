var DamageTypes = {
    nSlashing: "Non-Magical Slashing",
    nPierceing: "Non-Magical Piercing",
    nBludgeoning: "Non-Magical Bludgeoning",
    Slashing: "Slashing",
    Piercing: "Piercing",
    Bludgeoning: "Bludgeoning",
    Acid: "Acid",
    Cold: "Cold",
    Fire: "Fire",
    Force: "Force",
    Lightning: "Lightning",
    Necrotic: "Necrotic",
    Poison: "Poison",
    Psychic: "Psychic",
    Radiant: "Radiant",
    Thunder: "Thunder",

}

var ConditionTypes = {
    Blinded: "Blinded",
    Charmed: "Charmed",
    Deafened: "Deafened",
    Fatigued: "Fatigued",
    Frightened: "Frightened",
    Grappled: "Grappled",
    Incapacitated: "Incapacitated",
    Invisible: "Invisible",
    Paralyzed: "Paralyzed",
    Petrified: "Petrified",
    Poisoned: "Poisoned",
    Prone: "Prone",
    Restrained: "Restrained",
    Stunned: "Stunned",
    Unconscious: "Unconscious",
    Exhaustion: "Exhaustion"
}

class Creature{
    constructor(name, race, health, AC, str, dex, con, int, wis, cha, speed=30, climb=0, fly=0, burrow=0){
        this.name = name;
        this.race = race;
        this.maxHealth = health;
        this.heath = health;
        this.AC = AC;
        this.str = str;
        this.dex = dex;
        this.con = con;
        this.int = int;
        this.wis = wis;
        this.cha = cha;
        this.speed = speed;
        this.climb = climb;
        this.fly = fly;
        this.burrow = burrow;
    }

    set Resistances(arr){
        this.resistances = arr;
    }

    get Resistances(){
        return this.resistances;
    }

    set Immunities(arr){
        this.immunities = arr;
    }

    get Immunities(){
        return this.immunities;
    }

    set Vulnerabilities(arr){
        this.vulnerabilities = arr;
    }

    get Vulnerabilities(){
        return this.immunities;
    }

    set ConditionImmunities(arr){
        this.condImm = arr;
    }

    get ConditionImmunities(){
        return this.condImm;
    }

    set PassivePerception(val){
        this.PP = val;
    }

    get PassivePerception(){
        return this.PP;
    }

    set Perseption(arr){
        this.perception
    }

    set MaxHealth(val){
        this.maxHealth = val;
    }

    TakeDamage(val){
        this.heath -= val;
    }

    Heal(val){
        this.heath += val;
    }

    addAttribute(val){
        this.attributes.push(val);
    }

    addAction(val){
        this.actions.push(val);
    }

    addReaction(val){
        this.addReaction.push(val);
    }

    addEquipment(val){
        this.equiment.push(val);
    }

    addAffliction(val){
        this.afflictions.push(val);
    }
};

class Affliction{
    constructor(description, duration){
        this.description = description;
        this.duration = duration;
    }
}
